<script setup>
// const number = 31;
// const animal = "goat";
// const searchUrl = "https://www.pexels.com/search/"

const message = "Welcome. Get ready to maser Vue.Js 3!"
const date = "<strong>30th June, 2023</strong>"



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

<template>

    <div>
        <h1 class="text-2xl text-white-900">{{ message }}</h1>
        <h1 class="text-xl text-white-900">Today is <span v-html="date" class="text-blue-700"></span></h1>
    </div>

</template>

<style scoped>

</style>