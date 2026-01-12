<script setup>
    import {ref} from 'vue'
    const copyright_year = ref("2026")
</script>

<template>
  <footer>
    <p>&copy; {{copyright_year}}</p>
  </footer>
</template>

<style scoped>
footer {
  position: fixed;
  bottom: 0;
  padding-bottom: 20px;
}
footer p {
  color: blue
}
</style>