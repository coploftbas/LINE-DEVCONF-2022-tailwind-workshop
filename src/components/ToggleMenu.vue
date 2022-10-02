<template>
  <div class="flex justify-between items-center h-12 pr-4 ml-4">
    <div class="text-lg">{{ label }}</div>
    <ToggleSwitch />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import ToggleSwitch from '@/components/ToggleSwitch.vue'

export default defineComponent({
  name: 'ToggleMenu',
  props: {
    label: String,
  },
  components: {
    ToggleSwitch,
  }
})
</script>