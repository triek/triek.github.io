<template>
  <component :is="as" :class="customClass">
    <slot />
  </component>
</template>

<script setup>
const props = defineProps({
  as: {
    type: String,
    default: 'div',
  },
  customClass: {
    type: [String, Array, Object],
    default: '',
  },
});
</script>
