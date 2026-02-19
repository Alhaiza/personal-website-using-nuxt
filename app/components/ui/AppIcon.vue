<script setup lang="ts">
const { name, size, customClass } = defineProps({
    name: {
        type: String,
        required: true,
    },
    size: {
        type: String,
        default: 'md'
    },
    customClass: {
        type: String,
        default: ''
    }
})

const sizeClass = computed(() => {
  if (size === 'sm') return 'text-sm'
  if (size === 'lg') return 'text-2xl'
  return 'text-xl'
})
</script>
<template>
    <Icon
    :name="name"
    :class="['inline-block', sizeClass]"
  />
</template>