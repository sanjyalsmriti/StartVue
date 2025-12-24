<script setup>
    import {ref} from 'vue'
    const name = ref('Smiriti')
    const lastName = ref('sanjyal')
</script>

<template>

    <main>
        <h1>Hello, {{ name }}!</h1>
<p>iam about to learn <a href="https://vuejs.org/" target="_blank">Vue.js</a></p>
    </main>
</template>

<style scoped>
main {
  min-height: 50vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

main h1 {
  margin-bottom: 0.5rem;
}

main p {
  margin-top: 0;
}


</style>