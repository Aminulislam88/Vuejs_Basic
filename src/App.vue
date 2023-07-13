<script setup>
import {data} from './Data/data.js'

</script>

<template>
<div class="container mx-auto flex items-center justify-center min-h-screen flex-col">
  <h1 class="text-4xl">{{data.messeage}}</h1>

  <h2 class="mt-10 text-xl text-gray-700">Today is <span>{{data.date}}</span></h2>

</div>
</template>

<style scoped>

</style>
