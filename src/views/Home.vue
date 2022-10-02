<template>
  <div class="p-4 fixed bg-white flex flex-col w-full h-full top-0 left-0">
    <div>
      <img
        src="../assets/images/cover.jpg"
        alt="Fashion Up Your Look"
        class="rounded-lg mb-5">
      <h1 class="text-2xl my-5">Fashion Up Your Look</h1>
      <p>Welcome to the world's most marketplace. Buying and Selling of goods or services using the internet.</p>
    </div>
    <Button
      class="h-12 bg-blue-500 b text-white text-lg w-full mt-auto rounded-lg">Get Started</Button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Button from '@/components/Button.vue'

export default defineComponent({
  name: 'Home',
  components: {
    Button,
  },
})
</script>