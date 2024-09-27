<script setup>
import { ref } from "vue";

const props = defineProps(["item", "index"]);
const emit = defineEmits(["addItemToBasket"]);
const itemNumber = ref(1);

function resetNumber() {
  itemNumber.value = 1;
}
</script>

<template>
  <img :src="item.url" alt="" class="rounded-md" />
  <div class="flex flex-col gap-2 items-center justify-center py-2">
    <p>{{ props.item?.name }}</p>
    <p>{{ props.item?.description }}</p>
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
      class="bg-green-300 w-[200px] h-[40px] rounded-md group"
      @click="
        $emit('addItemToBasket', itemNumber, props.item?.id);
        resetNumber();
      "
      role="group"
    >
      add to basket
    </button>
  </div>
</template>
