<script setup>
import {data} from './Data/data.js'
// const messeage="Welcome. Get ready to master Vue.js 3!"
// const date="30th June, 2023"
// const data={
// messeage: "Welcome. Get ready to master Vue.js 3!",
//     date: "13th july 2023",
//     value:[1,2,3,4]
// }

//
// const arrdata=[
//   {
//     messeage: "Welcome. Get ready to master Vue.js 3!",
//     date: "13th july 2023",
//   },
//   {
//     value:[1,2,3,4]
//   }
//
// ]

// function getDate(){
//   return "7th july 2023"
// }
// function oddOrEven(n){
//   if (n%2==0){
//     return "Even"
//   }
//   return "odd"
// }
// function letDate(){
//   const date=new Date();
//   return date.toDateString();
// }
// const number=15
</script>

<template>
<div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
  <h1 class="text-4xl">{{data.messeage}}</h1>
<!--  <h2 class="mt-10 text-xl text-gray-700">Today is <span>{{date}}</span></h2>-->
  <h2 class="mt-10 text-xl text-gray-700">Today is <span>{{data.date}}</span></h2>
<!--  <h2 class="mt-10 text-xl text-gray-700">Number is <span> {{oddOrEven(5)}}</span></h2>-->
<!--  <h2 class="mt-10 text-xl text-gray-700">{{number}}  is {{number%2==0 ? "even" : "odd"}}</h2>-->
<!--  <h2 class="mt-10 text-xl text-gray-700">Today is <span>{{arrdata[1].value[2]}}</span></h2>-->
</div>
</template>

<style scoped>

</style>
