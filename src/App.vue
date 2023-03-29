<script setup>
import { RouterView } from 'vue-router'
import TodoHeader from '@/components/TodoHeader.vue';
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>

<!-- This could also be saved in 'assets/' then imported into 'main.js': import '@/assets/main.scss' -->
<style lang="scss">
/* CSS code from https://github.com/johnkomarnicki/vue-3-crash-course/blob/section-4/src/App.vue */
@import url("https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;700&display=swap");
* {
  font-family: "Rubik", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
