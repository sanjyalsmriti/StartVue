<script setup>
    import { ref } from 'vue';
const copyright_year = ref(new Date().getFullYear())
</script>

<template>
    <footer>
         <p>&copy; {{ copyright_year }}</p>
    </footer>
</template>

<style scoped>
footer {
  height: 10vh;
  display: flex;
  justify-content: center;
  align-items: center;
  opacity: 0.7;
}

</style>