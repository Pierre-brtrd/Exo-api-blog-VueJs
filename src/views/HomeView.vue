<template>
  <div class="content">
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </div>
  <section class="main">
    <h1 class="green">Welcome to Vue 3 + Vite</h1>
  </section>
</template>

<script setup>
import HelloWorld from '@/components/HelloWorld.vue'
</script>

<style scoped>
.content {
  line-height: 1.5;
  height: 80vh;
  width: 50%;
  float: left;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.main {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 80vh;
  width: 50%;
  margin-left: auto;
  margin-right: auto;
}
</style>