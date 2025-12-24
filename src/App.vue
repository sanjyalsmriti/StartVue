<script setup>
  import {ref} from 'vue'
  const name = ref('Smiriti')
const emoji = ref("👋")
const copyright_year = ref('2025')
</script>

<template>
  <header>
    <span>{{ emoji }}</span>
  </header>

  <main>
    <h1>Hello, {{ name }}!</h1>
<p>iam about to learn <a href="https://vuejs.org/" target="_blank">Vue.js</a></p>
  </main>

  <footer>
    <p> &copy; {{copyright_year}}</p>
  </footer>

</template>

<style scoped>
  header span{
    font-size: 3rem;
  }
  main h1{
    display: block;
  }
  main a{
    color: #42B883;
  }
  footer{
    position: fixed;
    bottom: 0;
    padding-bottom: 20px;
  } 
  footer p{
    color: blue;
  }


</style>