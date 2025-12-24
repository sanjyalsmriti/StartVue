<script setup>
import {ref} from 'vue'
const emoji = ref("👋")
</script>

<template>
    <header>
        <span>{{ emoji }}</span>
    </header>

</template>

<style scoped>
header {
  height: 20vh;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 3rem;
}


</style>
