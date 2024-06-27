<script setup>
defineProps({
  image: String,
  description: String,
  price: Number,
  name: String,
});
</script>

<template>
  <div class="content-center mx-5">
    <div class="bg-white space-y-3 border-2 rounded-xl p-2">
      <div class="content-center mx-auto justify-center">
        <div class="block">
          <img class="bg-white py-4" width="220" src="~assets/img/1.png" alt="Product Image">

        </div>
      </div>
      <div class="rounds flex space-x-2">
        <div class="box w-6 h-6 rounded-full" style="background: #C47530;"></div>
        <div class="box w-6 h-6 rounded-full" style="background: #FAC585;"></div>
        <div class="box w-6 h-6 rounded-full" style="background: #05697C;"></div>

      </div>
      <div class="w-40 space-y-6 text-2xl font-extrabold">
        {{ name }}
      </div>
      <div class="w-40 space-y-6">
        {{ description }}
      </div>
      <div class="flex flex-row justify-between p-3">
        <div class="flex-col font-bold text-xl">${{ price }}</div>
        <div class="flex-col rounded-xl border-pink-500 text-pink-500 border p-1 fill-transparent border-spacing-2">BUY
        </div>
      </div>
    </div>
  </div>
</template>
