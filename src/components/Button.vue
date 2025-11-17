<template>
  <component :is="as" :href="href" :type="as === 'button' ? type : undefined" :class="customClass">
    <slot />
  </component>
</template>

<script setup>
const props = defineProps({
  as: {
    type: String,
    default: 'button',
  },
  href: {
    type: String,
    default: undefined,
  },
  type: {
    type: String,
    default: 'button',
  },
  customClass: {
    type: [String, Array, Object],
    default: '',
  },
});
</script>
