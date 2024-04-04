<template>
    

    
    <p> Count :: {{ count }}</p>

    <button @click="increment">Increment</button>

    
</template>

<script setup>

import {ref} from 'vue';

let count= ref(0)


const counter= ()=>{
  console.log('clicked')
}



</script>