<!---->

<template>

  <div class="home">

    <h1>{{ message }}</h1>

  </div>

</template>

<script setup>
 import { ref } from 'vue'; const message=ref("Hello World")
</script>

<style scoped>
.home {
}
</style>

