<!-- <script scoped src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script> -->
<style scoped>
.marquee-row {
    width: 100%;
    overflow-x: hidden;
}

.marquee-block {
    position: relative;
    display: flex;
    width: 100%;
    animation-duration: 20s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    justify-content: space-between;
}

.marquee-item-list {
    display: inline-flex;
}

.marquee-item-list li {
    font-size: large;
    width: 100%;
    list-style: none;
    padding-right: 30px;
    white-space: nowrap
}

.marquee1 {
    animation-name: marquee1;
}


@keyframes marquee1 {
    0% {
        right: 0;
    }

    100% {
        right: 100%;
    }
}
</style>
<!-- 
<script scoped>
var elements = $('ul.marquee-item-list li').length;
for(var i=0;i < elements; i++){
 $(".marquee-item-list").clone().prependTo( ".marquee-block" );
};
var liEle = [];
var liEle = $(".marquee-item-list li");
</script> -->
<template>
    <div class="flex justify-between h-lvh">
        <div class="space-y-6 flex-1 justify-between content-evenly my-auto">
            <div class="text-8xl text-left font-bold">
                New Summer Collection
            </div>
            <div class="text-gray-800 text-lg">
                Shop the best clothes in the world
            </div>
            <div>
                <span class="p-3 rounded-full" style="background-color:#E08CFF">Shop Now</span>
            </div>

        </div>
        <div class="">
            <img class='mx-2 rounded-lg' style="width: 384px; height: 582px; " src="~assets/img/HeroImage.jpeg" alt="">
        </div>
    </div>
    <div class="marquee-row  bg-white border-6">
        <div class="marquee-block marquee1 border-double">
            <ul class="marquee-item-list ">
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
                <li>Customer Support ⚫   </li>
            </ul>
        </div>
    </div>

    <!--
    width: 384px;
height: 582px;
gap: 0px;
opacity: 0px;
 
     -->

















</template>