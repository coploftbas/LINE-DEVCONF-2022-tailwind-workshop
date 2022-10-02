<template>
  <div class="bg-white rounded-lg shadow divide-y mb-4 mx-4">
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Section',
})
</script>