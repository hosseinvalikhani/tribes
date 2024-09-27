<script setup>
const props = defineProps(["item", "products"]);
const emit = defineEmits(["updateQuantity"]);
console.log("product:", props.products);

function supply(id) {
  return props.products.find((item) => item.id === id).supply;
}
</script>

<template>
  <!-- {{ props.item }} -->
  <img :src="props.item.url" alt="" class="w-12 h-12 rounded-md" />
  <p>{{ props.item.name }}</p>

  <div class="flex items-center justify-center gap-2 w-[80px]">
    <button
      @click="$emit('updateQuantity', props.item.quantity - 1, item.id)"
      :disabled="props.item.quantity <= 1"
    >
      <img
        class="w-[20px] h-[20px] bg-white"
        src="./../assets/img/minus-circle-svgrepo-com.svg"
        alt=""
        :class="props.item.quantity <= 1 ? 'opacity-45' : ''"
      />
    </button>
    <p>{{ props.item.quantity }}</p>
    <button
      @click="$emit('updateQuantity', props.item.quantity + 1, props.item.id)"
      :disabled="props.item.quantity >= supply(item.id)"
    >
      <img
        class="w-[20px] h-[20px] bg-white"
        src="./../assets/img/plus-svgrepo-com.svg"
        alt=""
        :class="props.item.quantity >= supply(item.id) ? 'opacity-45' : ''"
      />
    </button>
  </div>
</template>
