<template>
  <form :action="action" :method="method" :class="customClass" role="form" @submit="emit('submit', $event)">
    <slot />
  </form>
</template>

<script setup>
const props = defineProps({
  action: {
    type: String,
    default: '#',
  },
  method: {
    type: String,
    default: 'get',
  },
  customClass: {
    type: [String, Array, Object],
    default: '',
  },
});

const emit = defineEmits(['submit']);
</script>
