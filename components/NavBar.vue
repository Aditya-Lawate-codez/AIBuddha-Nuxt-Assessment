<template class="sticky">
    <div style="border-bottom: #E08CFF;"
        class="row flex my-4 mx-3 h-10 my-30 border-spacing-y-60 border-b top-6 sticky ">
        <div class='col'>
            <NuxtLink to="/"><span style="color:#E08CFF;">Go</span> Shop</NuxtLink>
        </div>
        <div class='col flex space-evenly content-center space-x-5 bg- mx-auto'>
            <div class="hover:underline cursor-pointer">
                <NuxtLink to="/">Home</NuxtLink>
            </div>
            <div class="hover:underline cursor-pointer">
                <NuxtLink to="/about">About us</NuxtLink>
            </div>
            <div class="hover:underline cursor-pointer">
                <NuxtLink to="/service">Services</NuxtLink>
            </div>
            <div class="hover:underline cursor-pointer">
                <NuxtLink to="/contact">Contact</NuxtLink>
            </div>

        </div>
        <div class='col'>
            <NuxtLink to="/login">Login / Register</NuxtLink>

        </div>
    </div>
</template>