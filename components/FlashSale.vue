<script setup>
import ClothCard from '~/components/ClothCard.vue';

const products = [
    { image: '~assets/img/1.png', description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nobis?', price: 120, name:"Blazer" },
    { image: '~assets/img/2.png', description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nobis?', price: 110, name:"T shirt" },
    { image: '~assets/img/3.png', description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. A, nobis?', price: 100, name: "Black Casual"},
];
</script>

<template>
    
    <div class="flex flex-col py-10 ">
        <div class="text-center text-2xl font-bold">Flash Sale</div>
        <div class="flex flex-row my-5 content-center m-auto space-x-7 ">
            <div class="hover:underline cursor-pointer">Men</div>
            <div class="hover:underline cursor-pointer">Women</div>
            <div class="hover:underline cursor-pointer">Kids</div>
            <div class="hover:underline cursor-pointer">Accessories</div>
        </div>
        <div class="flex flex-wrap justify-center content-center p-5">
            <ClothCard v-for="(product, index) in products" :key="index" :image="product.image"
             :name="product.name"   :description="product.description" :price="product.price" />
        </div>
    </div>
</template>
