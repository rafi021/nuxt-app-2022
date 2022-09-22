<template>
    <button @click="increment" class="btn btn-primary">+</button>
    <p class="count">{{ count }}</p>
    <button @click="decrement" class="btn">-</button>
</template>

<script setup>
    const count = ref(0);
  
    function increment(){
      count.value++; 
    }
    function decrement(){
      count.value--; 
    }
</script>
  
<style>
    .count{
      font-size: 50px;
    }
    .btn{
      padding: 10px 30px;
    }
    .btn-primary{
      background-color: rgb(115, 247, 115);
      color: #fff;
      font-size: 20px;
      font-weight: bold;
    }
    .btn-secondary{
      background-color: rgb(244, 79, 79);
      color: #fff;
      font-size: 20px;
      font-weight: bold;
    }
</style>