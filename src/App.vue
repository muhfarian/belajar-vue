<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjYBvYhb1jcsxvUN6ZZO1VWZ0w_C1R2XrpOQ&usqp=CAU" width="1000" height="200" />


    <div class="wrapper">
      <HelloWorld msg="Ini Web" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
  div{
    font-family: monospace;
    font-size: 500%;
  }
</style>
