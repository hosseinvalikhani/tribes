<!-- <script setup>
import { ref } from "vue";

const basket = ref([]);

const mobileInfo = ref([
  {
    url: "/src/assets/img/iphone13pro.webp",
    name: "iPhone 13 Pro",
    description:
      "Apple's premium phone with A15 Bionic chip and advanced camera features.",
    supply: 10,
  },
  {
    url: "/src/assets/img/honorX7B.webp",
    name: "Honor X7B",
    description:
      "Affordable device with a large display and long battery life.",
    supply: 10,
  },
  {
    url: "/src/assets/img/honorX9A.webp",
    name: "Honor X9A",
    description: "Mid-range phone with curved OLED display and fast charging.",
    supply: 10,
  },
  {
    url: "/src/assets/img/honorX9B.webp",
    name: "Honor X9B",
    description:
      "Stylish design with high durability and powerful performance.",
    supply: 10,
  },
  {
    url: "/src/assets/img/honor90.webp",
    name: "Honor 90",
    description:
      "Latest flagship phone with a 200MP camera and AI-enhanced photography.",
    supply: 10,
  },
  {
    url: "/src/assets/img/s21ultra.webp",
    name: "Samsung Galaxy S21 Ultra",
    description:
      "Samsung's top-tier model with a 108MP camera and 100x Space Zoom.",
    supply: 10,
  },
]);

const isMobileInBasket = (index) => {
  // Get the name of the mobile at the specified index
  const mobileName = mobileInfo.value[index]?.name;

  // Check if the basket includes this mobile name
  return basket.value.some((basketItem) => basketItem.name === mobileName);
};
const basketIndex = (index) => {
  // Get the name of the mobile at the specified index
  const mobileName = mobileInfo.value[index]?.name;
  // Check if the basket includes this mobile name
  return basket.value.findIndex((basketItem) => basketItem.name === mobileName);
};

function addToBasket(index) {
  console.log(basket.value);
  console.log(mobileInfo.value[index]?.name);

  const existingItem = isMobileInBasket(index);
  let indexInBasket = basketIndex(index);
  mobileInfo.value[index].supply--;

  console.log(mobileInfo.value[index].supply);
  if (existingItem) {
    console.log(indexInBasket);
    // If the item exists in the basket, increase the quantity
    basket.value[indexInBasket].quantity++;
  } else {
    // If the item does not exist, create the object and push it to the basket
    const newItem = {
      url: mobileInfo.value[index]?.url,
      name: mobileInfo.value[index]?.name,
      quantity: 1, // Set initial quantity to 1
    };
    basket.value.push(newItem);
  }

  console.log(basket.value); // Log the basket to check the items
}
// function addToBasket(index) {
//   console.log("is", isMobileInBasket(index));
// }
</script> -->
<script setup>
import { ref } from "vue";
import cardComponent from "./cardComponent.vue";
import BasketComponent from "./basketComponent.vue";
const basket = ref([]);

const mobileInfo = ref([
  {
    url: "/src/assets/img/iphone13pro.webp",
    name: "iPhone 13 Pro",
    description:
      "Apple's premium phone with A15 Bionic chip and advanced camera features.",
    supply: 10,
    id: 11,
  },
  {
    url: "/src/assets/img/honorX7B.webp",
    name: "Honor X7B",
    description:
      "Affordable device with a large display and long battery life.",
    supply: 10,
    id: 12,
  },
  {
    url: "/src/assets/img/honorX9A.webp",
    name: "Honor X9A",
    description: "Mid-range phone with curved OLED display and fast charging.",
    supply: 10,
    id: 13,
  },
  {
    url: "/src/assets/img/honorX9B.webp",
    name: "Honor X9B",
    description:
      "Stylish design with high durability and powerful performance.",
    supply: 10,
    id: 14,
  },
  {
    url: "/src/assets/img/honor90.webp",
    name: "Honor 90",
    description:
      "Latest flagship phone with a 200MP camera and AI-enhanced photography.",
    supply: 10,
    id: 15,
  },
  {
    url: "/src/assets/img/s21ultra.webp",
    name: "Samsung Galaxy S21 Ultra",
    description:
      "Samsung's top-tier model with a 108MP camera and 100x Space Zoom.",
    supply: 10,
    id: 16,
  },
]);
function addToBasket(number, id) {
  const mobile = mobileInfo.value.find((item) => item.id === id);

  if (!mobile || mobile.supply <= 1 || number > mobile.supply) {
    console.log("Item not available or out of stock");
    return 0;
  }
  // Find the item in the basket by its name
  const existingItem = basket.value.find(
    (basketItem) => basketItem.name === mobile.name
  );
  // Decrease the mobile supply
  if (existingItem && mobile.supply > 0) {
    // If the item already exists, increment the quantity
    existingItem.quantity += number;
    mobile.supply -= number;
  } else if (!existingItem && mobile.supply > 0) {
    // If the item doesn't exist in the basket, add it with a quantity of 1
    basket.value.push({
      url: mobile.url,
      name: mobile.name,
      quantity: number,
      id: mobile.id,
    });
    mobile.supply -= number;
  }
  console.log("mobile", mobile);

  console.log(basket.value); // Log the updated basket
}
function updateBasket(quantity, id) {
  console.log("quentity:", quantity, "id:", id);
  const mobile = mobileInfo.value.find((item) => item.id === id);
  const basketItem = basket.value.find(
    (basketItem) => basketItem.id === mobile.id
  );
  basketItem.quantity = quantity;
}

function showBasket() {
  if (basket.value.length === 0) return;
  const basketComponent = document.querySelector(".basket");
  basketComponent.classList.toggle("hidden");
  basketComponent.classList.toggle("block");
}
</script>

<template>
  <nav class="flex items-center justify-between">
    <ul class="flex justify-center items-center gap-6">
      <li><a href="#">blog</a></li>
      <li><a href="#">Contact us</a></li>
    </ul>
    <ul class="relative">
      <li class="w-12 h-12">
        <button @click="showBasket">
          <img src="./../assets/img/basket.png" alt="" />
        </button>
      </li>
    </ul>
  </nav>
  <div
    class="basket hidden absolute right-8 bg-slate-50 z-10 max-h-[300px] overflow-auto"
  >
    <ul class="grid grid-cols-1 gap-4 p-4">
      <li
        v-for="(item, index) in basket"
        :key="index"
        class="flex items-center justify-between px-2"
      >
        <BasketComponent
          :item="item"
          :products="mobileInfo"
          @update-quantity="updateBasket"
        ></BasketComponent>
      </li>
    </ul>
  </div>
  <ul class="grid grid-cols-1 gap-4 sm:grid-cols-2 lg:grid-cols-4">
    <!-- <li
      v-for="(item, index) in mobileInfo"
      :key="index"
      class="flex flex-col border-black border-2"
    ></li> -->
    <li
      v-for="(item, index) in mobileInfo"
      :key="index"
      class="flex flex-col items-center justify-center border-black border-2 z-0"
    >
      <cardComponent
        :item="item"
        :basket="basket"
        :index="index"
        @add-item-to-basket="addToBasket"
      ></cardComponent>
    </li>
  </ul>
</template>

<style scoped></style>
