<template>
  <img
    alt="Vue logo"
    src="../assets/logo.png"
  >
  <Suspense>
    <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + Firebase" />
  </Suspense>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import HelloWorld from '../components/HelloWorld.vue'

export default defineComponent({
  name: 'Home',
  components: {
    HelloWorld
  }
})
</script>
