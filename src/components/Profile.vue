<template>
  <div class=" flex items-center p-4">
    <img 
      class=" w-14 h-14 mr-4 rounded-full"
      src="@/assets/images/avatar.jpg" alt="Maxwell">
    <div class="text--2xl ">Hello, Maxwell</div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Profile',
})
</script>