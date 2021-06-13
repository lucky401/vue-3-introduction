<script setup lang="ts">
import { ref } from 'vue'
const isRendered = ref(false)
</script>

<template>
  <div flex="~" class="flex-col justify-center items-center">
    <h1>Portals Example</h1>
    <button
      border="~ gray-400 opacity-50 rounded-lg"
      p="2"
      class="mt-6"
      font="mono"
      outline="!none"
      hover:bg="gray-400 opacity-20"
      @click="isRendered = !isRendered"
    >
      Render Content
    </button>
    <Teleport to="#teleport-target" v-if="isRendered">
      <div>Hello World!</div>
    </Teleport>
    <div id="teleport-target" class="m-8"></div>
  </div>
  
</template>
