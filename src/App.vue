<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheHeader from './components/Layout/TheHeader.vue'
</script>

<template>
  <TheHeader />
  <div class="content">
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />

    <div class="wrapper">
      <HelloWorld msg="You did it!" />
    </div>
  </div>

  <RouterView />
</template>

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
</style>
