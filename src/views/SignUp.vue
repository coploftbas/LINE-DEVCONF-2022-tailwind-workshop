<template>
  <div class="bg-white p-4 fixed flex-col w-full h-full top-0 left-0 flex space-between">
    <h1 class="flex justify-center text-2xl my-5">Create an account</h1>
    <div class="space-y-5">
      <InputText type="text" label="Fullname" placeholder="First name and Last name" />
      <InputText type="email" label="Email" placeholder="Enter email address" />
      <InputText type="password" label="Password" placeholder="Enter password" />
    </div>
    <Button class="h-12 bg-blue-500 b text-white text-lg w-full mt-auto rounded-lg">Register</Button>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Button from '@/components/Button.vue'
import InputText from '@/components/InputText.vue'

export default defineComponent({
  name: 'SignUp',
  components: {
    Button,
    InputText,
  },
})
</script>