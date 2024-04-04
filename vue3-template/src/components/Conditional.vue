<template>
    
    <div>
  <p>Hello</p>
  <h2 v-if="flag">Hello agin</h2>
  <h2 v-else>Hello yhid is else</h2>


    </div>
</template>

<script setup>
import {ref} from 'vue';

let flag= ref(true);

</script>