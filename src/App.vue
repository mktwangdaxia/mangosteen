<script setup lang="ts">
  import {ref} from 'vue';
  const count =ref(0)
  const onClick=()=>{
    count.value +=1
  }
</script>
<template>
  <div>
    {{count}}
  </div>
  <div>
  <button @click="onClick">+1</button>
  </div>
</template>

<style lang="" scoped>
  
</style>