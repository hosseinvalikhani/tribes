<script setup>
import { ref } from "vue";

const props = defineProps(["item", "index"]);
const emit = defineEmits(["addItemToBasket"]);
const itemNumber = ref(1);
// console.log("item is", props.item);
function resetNumber() {
  itemNumber.value = 1;
}
</script>

<template>
  <img
    :src="item.image"
    alt=""
    class="w-full h-full object-cover object-center"
  />
  <div class="flex flex-col gap-2 w-full py-2">
    <div class="flex justify-between text-left">
      <p class="text-left">{{ props.item?.title }}</p>
      <div v-if="props.item.detail.discounted_price" class="flex gap-2">
        <p class="opacity-60 line-through">{{ props.item.detail.price }}</p>
        <p>{{ props.item.detail.discounted_price }}</p>
      </div>
      <div v-else>
        <p>{{ props.item.detail.price }}</p>
      </div>
    </div>
    <p class="text-left">{{ props.item?.aims }}</p>
    <div class="flex items-center justify-between w-full">
      <div class="flex items-center justify-center gap-4">
        <button @click="itemNumber--" :disabled="itemNumber <= 1">
          <img
            class="w-[20px] h-[20px] bg-white"
            src="./../assets/img/minus-circle-svgrepo-com.svg"
            alt=""
            :class="itemNumber <= 1 ? 'opacity-45' : ''"
          />
        </button>
        <p>{{ itemNumber }}</p>
        <button @click="itemNumber++" :disabled="itemNumber >= item.supply">
          <img
            class="w-[20px] h-[20px] bg-white"
            src="./../assets/img/plus-svgrepo-com.svg"
            alt=""
            :class="itemNumber >= item.supply ? 'opacity-45' : ''"
          />
        </button>
      </div>
      <button
        class="bg-green-300 rounded-full px-4 py-2"
        @click="
          $emit('addItemToBasket', itemNumber, props.item?.id);
          resetNumber();
        "
        role="group"
      >
        add to basket
      </button>
    </div>
  </div>
</template>
