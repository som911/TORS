<template>
  <p>{{ hello }}</p>
  <HelloWorld msg="Vite + Vue" />
</template>
<script setup lang="ts">
import HelloWorld from "./components/HelloWorld.vue";
const hello: string = "Hello, Vue 3 with TypeScript!";
</script>

<style lang="scss">
    p {
        color: var(--w1);
    }
</style>
