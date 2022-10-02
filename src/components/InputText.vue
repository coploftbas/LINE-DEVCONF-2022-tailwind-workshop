<template>
  <div class="">
    <LabelText class="pb-1">{{ label }}</LabelText>
    <div class="bg-white flex items-center h-12 p-4 rounded-lg border-2 border-black-100">
      <div v-if="type" class="flex-none p-2">
        <font-awesome-icon v-if="type === 'text'" :icon="['fas', 'user']" />
        <font-awesome-icon v-if="type === 'password'" :icon="['fas', 'key']" />
        <font-awesome-icon v-if="type === 'email'" :icon="['fas', 'envelope']" />
      </div>
      <input :type="type" :placeholder="placeholder" class="flex-1 w-full">
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import LabelText from '@/components/LabelText.vue'

export default defineComponent({
  name: 'InputText',
  components: {
    LabelText,
  },
  props: {
    label: String,
    placeholder: String,
    type: String
  },
})
</script>