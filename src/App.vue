<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="./assets/muhfarian.png" height="50" />


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
