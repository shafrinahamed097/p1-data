<script setup>
// const number = 31;
// const animal = "goat";
// const searchUrl = "https://www.pexels.com/search/"

// const message = "Welcome. Get ready to maser Vue.Js 3!"
// const date = "<strong>30th June, 2023</strong>"

const location = "Dhaka"
const weather = ""



</script>

<!-- <template>
    <div>
        <h1 class="text-2xl text-blue-600 dark:text-sky-400" >Welcome. Get ready to master Vue.Js 3!</h1>
        <h1 class="text-xl">{{ number  }}/4 = <span>  {{ number/4 }} .</span>  </h1>
        <h1 class="text-xl">{{ number }} is {{ number % 2 == 0 ? "Even" : "Odd"  }} number</h1>
        <h2 class="text-xl">
            <a target="_blank" :href="searchUrl+animal.toUpperCase()">Search For {{ animal }}</a>
        </h2>
        
        <h2 class="text-xl">
            <a target="_blank" :href="`https://www.pexels.com/search/${animal.toLowerCase()}`">Search For {{ animal }}</a>
        </h2>
    </div>

</template> -->

<!-- <template>

    <div>
        <h1 class="text-2xl text-white-900">{{ message }}</h1>
        <h1 class="text-xl text-white-900">Today is <span v-html="date" class="text-blue-700"></span></h1>
    </div>

</template> -->


<template>
    <section class="container mx-auto flex items-center flex-col">
        <h1 class="text-center text-2xl py-10" >Login in Vue.js</h1>
        <div class="w-1/3  p-10 flex items-center flex-col space-y-10 bg-blue-800">
            <h1  class="text-3xl " >{{ location }}</h1>
            <h2 class="text-2xl" v-if="weather==='s'">Weather: Sunny</h2>
            <h2 class="text-2xl" v-else-if="weather==='c'">Weather: Cold</h2>
            <h2 class="text-2xl" v-else-if="weather==='r'">Weather: Rainy</h2>
            <h2 class="text-2xl" v-else>Weather: Cyclone</h2>
            <img v-if="weather==='s'" src="https://cdn.creazilla.com/cliparts/38457/sun-hot-clipart-md.png" alt="">
            <img v-else-if="weather==='c'" src="https://cdn.creazilla.com/icons/3432746/snowy-icon-md.png" alt="">
            <img v-else-if="weather==='r'" src="https://cdn.creazilla.com/cliparts/63069/weather-icon-clipart-md.png" alt="">
            <img v-else src="https://cdn.creazilla.com/cliparts/1723266/tornado-clipart-md.png" alt="">

        </div>

    </section>
</template>
<style scoped>

</style>