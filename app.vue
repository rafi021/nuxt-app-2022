<template>
  <div>
  <button @click="toggle">Toggle</button>
  <component :is="MyComponent" />
  </div>
</template>

<script setup>
  const MyComponent = shallowRef(resolveComponent('Counter'));

  function toggle(){
    MyComponent.value = resolveComponent('HomeWelcome');
  }
</script>