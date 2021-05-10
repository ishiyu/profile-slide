<script setup lang="ts">
import { computed, defineProps } from 'vue'
import { handleBackground } from '@slidev/client/layoutHelper'
const props = defineProps({
  image: {
    type: String,
  },
  class: {
    type: String,
  },
})
const style = computed(() => handleBackground(props.image))
</script>

<template>
  <div class="grid grid-cols-2 w-full h-full">
    <div class="slidev-layout default" :class="props.class">
      <slot />
    </div>
    <div class="w-full h-full" style="padding: 25%;">
      <div class="w-full h-full" :style="style"></div>
    </div>
  </div>
</template>
