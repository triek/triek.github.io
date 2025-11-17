<template>
  <div class="projects-thumb">
    <div class="projects-info">
      <small class="projects-tag">{{ tag }}</small>
      <a :href="link" target="_blank">
        <h3 class="projects-title">{{ title }}</h3>
      </a>
    </div>

    <a :href="image" class="popup-image">
      <img :src="image" class="projects-image img-fluid" alt="" />
    </a>
  </div>
</template>

<script setup>
const props = defineProps({
  tag: {
    type: String,
    required: true,
  },
  title: {
    type: String,
    required: true,
  },
  link: {
    type: String,
    required: true,
  },
  image: {
    type: String,
    required: true,
  },
});
</script>
