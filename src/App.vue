<!-- <script setup>
// const number = 31;
// const animal = "goat";
// const searchUrl = "https://www.pexels.com/search/"

// const message = "Welcome. Get ready to maser Vue.Js 3!"
// const date = "<strong>30th June, 2023</strong>"

// const location = "Dhaka"
// const weather = "s"


// const bgOrange = "bg-orange-400"
// const bgIndigo = "bg-indigo-400"
// const bgGreen = "bg-green-400"

// const weekday  = true

// const colors = {
//     bgColor:'bg-teal-100',
//     borderColor: 'border-teal-500',
//     textColor:'text-teal-900 '

// }

// const messageType = 'warning'
// if('error' ==  messageType){
//     colors.bgColor = 'bg-red-100'
//     colors.borderColor = 'border-red-500'
//     colors.textColor = 'bg-red-900'
// }

// else if('warning'=== messageType){
//     colors.bgColor = 'bg-yellow-100'
//     colors.borderColor = 'border-yellow-500'
//     colors.textColor = 'bg-yellow-900'
// }


const bgOrange = 'background-color: rgba(251,146,60,1)'
const bgIndigo = 'background-color:rgba(129,140,248,1)'
const bgGreen = 'background-color:rgba(52,11,153,1)'

const bgRed = 'background-color:rgba(220,38,38,1)'
const bgDarkGreen = 'background-color:rgba(5,150,105,1)'

const colors = {
    borderColor: 'rgba(20,184,166,1)',
    color:'rgba(19,78,74,1)',
    backgroundColor : 'rgba(204,251,241,1)'
    
}

const weekday = false

const messageType = 'success'
if('error' == messageType){
    colors.backgroundColor = 'rgba(254,226,226,1)'
    colors.color = 'rgba(127,29,29,1)'
}




</script> -->



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


<!-- <template>
    <section class="container mx-auto flex items-center flex-col">
        <h1 class="text-center text-2xl py-10" >Login in Vue.js</h1>
        <div class="w-1/3  p-10 flex items-center flex-col space-y-10 bg-blue-800">
            <h1  class="text-3xl " >{{ location }}</h1>
            
            <div v-show="weather==='s'">
                <h2 class="text-2xl" >Weather: Sunny</h2>
            <img  src="https://cdn.creazilla.com/cliparts/38457/sun-hot-clipart-md.png" alt="">
            </div>

           <div v-show="weather==='pc'">
            <h2 class="text-2xl" >Weather: Cold</h2>
            <img  src="https://cdn.creazilla.com/icons/3432746/snowy-icon-md.png" alt="">

           </div>
           
           <div v-show="weather==='r'">
            <h2 class="text-2xl" >Weather: Rainy</h2>
            <img  src="https://cdn.creazilla.com/cliparts/63069/weather-icon-clipart-md.png" alt="">

           </div>
            <div  v-show="weather==='c'">
                <h2 class="text-2xl">Weather: Cyclone</h2>
            <img src="https://cdn.creazilla.com/cliparts/1723266/tornado-clipart-md.png" alt="">
            </div>

        </div>

    </section>
</template> -->

<!-- <template>
    <section  class="container mx-auto">
        <h1 class="text-center text-3xl py-12" >Class & Style Binding</h1>
        <section class="flex space-x-10" >
            <div class="w-1/3  h-16" :class="bgIndigo"></div>
            <div class="w-1/3  h-16" :class="bgGreen" ></div>
            <div class="w-1/3  h-16" :class="bgOrange" ></div>

        </section>

        <section class="mt-10">
            <div class=" h-16 flex items-center justify-center text-white" :class="weekday ? 'bg-red-600 text-2xl': 'bg-green-600 text-4xl'">It's a weekday</div>
        </section>

        <section class="mt-10">
            <div class="border-t-4  rounded-b  px-4 py-3 shadow-md" :class="[colors.bgColor, colors.borderColor, colors.textColor]" role="alert">
                <p class="font-bold" >Our Privacy has changes</p>
                <p class="text-sm" >Make sure you know how these changes affect you.</p>

            </div>
        </section>

    </section>
</template> -->

<!-- <template>
    <section class="container mx-auto">
        <h1 class="text-center tex-3xl py-12" >Class & Style Binding</h1>

        <section class="flex space-x-10">
            <div class="w-80 b h-24" :style="bgOrange"></div>
            <div class="w-80 b h-24" :style="bgIndigo"></div>
            <div class="w-80 h-24" :style="bgDarkGreen"></div>
        </section>

        <section class="mt-10">
            <div class=" h-16 flex items-center justify-center text-white" :style="weekday==true ?[bgRed, 'font-size:20px']:[bgDarkGreen, 'font-size:35px']">It's a weekday</div>
        </section>

        <section class="mt-10">
            <div class=" border-t-4  rounded-b  px-4 py-3 shadow-md" :style="colors">
                <p class="font-bold" >Our Privacy policy has changed</p>
                <p class="text-sm" >Make sure you know how these changes affect you</p>

            </div>

        </section>
    </section>
</template> -->


<!-- <script setup>

const items = [1,2,3,4,5] // List Rendering

</script> -->

<!-- <template>
    <section>
        <div class="grid grid-flow-col grid-rows-5 gap-4 ">
            <div class="border-2 border-solid w-32 " v-for="item in items">{{ item }}</div>
            <div class="border-2 border-solid w-32 " v-for="n in 10">{{ n }}</div>
           
  
</div>
    </section>

</template> -->
<script setup>
  const tasks = [
    "Complete project proposal",
    "Update website content",
    "Fix bug in user authentication",
    "Prepare presentation sliders",
    "Test new features implementation"
  ];


  const tasks1 = [
    {id:1, title: "Complete project proposal", status: "In Progress"},
    {id:2, title: "Update website content", status: "Completed"},
    {id:3, title: "Fix bug in user authentication", status: "Pending"},
    {id:4, title: "Test new features implementation", status: "In Progress"},
    {id:5, title: "Prepare presentation sliders", status: "Completed"}
  ];

  function getCompletedTask(){
    return tasks1.filter(task=>"Completed"==task.status)
  }

  function getProgressTask(){
    return tasks1.filter(task=>"In Progress" == task.status )
  }

  function getPendingTask(){
    return tasks1.filter(task=>"Pending" == task.status)
  }

  const productDetails = [
    {
        id:1,
        title: "Card Title1",
        details: "A card component has a figure, a body part, and inside body there are title1 and actions parts",
        photo: "https://img.daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.webp"
    },
    {
        id:2,
        title: "Card Title2",
        details: "A card component has a figure, a body part, and inside body there are title2 and actions parts",
        photo: "https://img.daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.webp"
    },
    {
        id:3,
        title:"Card Title3",
        details: "A card component has a figure, a body part, and inside body there are title3 and actions parts",
        photo: 'https://img.daisyui.com/images/stock/photo-1606107557195-0e29a4b5b4aa.webp'
    }
  ];
  import {ref} from 'vue'
  const location = ref ("Noakhali");

  function changeLocation(newLocation){
    location.value = newLocation;
  }


</script>
<!-- 
<template>
    
        <section class="grid grid-flow-col grid-rows-5  ">
            <div class="border border-indigo-600  m-8" v-for="(task, index) in tasks">
              {{ index+1 }} .  {{ task }}
                
            </div> 

         <div class="border border-indigo-600  m-8" v-for="task in tasks1"  :key="tasks1.id">
             {{ task.id }}.  {{ task.title }}
                
            </div>
         
          
         <div class="border border-indigo-600  m-8" v-for="task in getCompletedTask()"  :key="tasks1.id">
            <h2 class="text-green-900 underline">Completed Task </h2> {{ task.id }}.  {{ task.title }}
                
            </div>

            <div class="border border-indigo-600  m-8" v-for="task in getProgressTask()"  :key="tasks1.id">
            <h2 class="text-yellow-900 underline">In Progress Task </h2> {{ task.id }}.  {{ task.title }}
                
            </div>

            <div class="border border-indigo-600  m-8" v-for="task in getPendingTask()"  :key="tasks1.id">
            <h2 class="text-yellow-900 underline">Pending Task </h2> {{ task.id }}.  {{ task.title }}
                
            </div>

          
        
    </section>
</template> -->


<!-- <template>

<article class="text-wrap">
  <h3>Beloved Manhattan soup stand closes</h3>
  <p>ew Yorkers are facing the winter chill...</p>
</article>

    <section>
        <div class="flex flex-nowrap gap-4">
          
            <div class="card bg-base-100 w-96 shadow-sm bg-black" v-for="productDetail in productDetails" :key="productDetail.id" >
  <figure>
    <img :class="2==productDetail.id?'h-64': ''"
      :src="productDetail.photo"
      alt="Shoes" />
  </figure>
  <div class="card-body">
    <h2 class="card-title">{{productDetail.title}}</h2>
    <p>{{ productDetail.details }}</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">Buy Now</button>
    </div>
  </div>
</div>


        </div>

       

        
    </section>

</template> -->


<template>
    <section>

        <h2 class="text-2xl mb-8">Events & Reactivity in Vue.js</h2>
        

        <div class="flex gap-4 w-80">
            <button class="btn  w-32 btn-primary" @click="changeLocation('Noakhali')">Noakhali</button>
            <button class="btn  w-32 btn-primary" @click = "changeLocation('Dhaka')">Dhaka</button>
            <button class="btn  w-32 btn-primary" @click = "changeLocation('Coxsbazar')">Coxsbazar</button>

        </div>

        <h2 class="text-2xl mt-8">Current Location is {{ location }}</h2>
    </section>
</template>
<style scoped>

</style>