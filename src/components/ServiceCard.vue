<template>
  <Card :customClass="['services-thumb', { 'services-thumb-up': elevated }, customClass]">
    <div class="d-flex flex-wrap align-items-center border-bottom mb-4 pb-3">
      <h3 class="mb-0">{{ title }}</h3>

      <div class="services-price-wrap ms-auto">
        <p class="services-price-text mb-0">{{ price }}</p>
        <div class="services-price-overlay"></div>
      </div>
    </div>

    <p>{{ description }}</p>

    <Button as="a" :href="buttonLink" :customClass="['custom-btn custom-border-btn btn mt-3']">{{ buttonText }}</Button>

    <div class="services-icon-wrap d-flex justify-content-center align-items-center">
      <i class="services-icon" :class="icon"></i>
    </div>
  </Card>
</template>

<script setup>
import Button from './Button.vue';
import Card from './Card.vue';

const props = defineProps({
  title: {
    type: String,
    required: true,
  },
  price: {
    type: String,
    required: true,
  },
  description: {
    type: String,
    required: true,
  },
  icon: {
    type: String,
    required: true,
  },
  buttonLink: {
    type: String,
    default: '#',
  },
  buttonText: {
    type: String,
    default: 'Discover More',
  },
  elevated: {
    type: Boolean,
    default: false,
  },
  customClass: {
    type: [String, Array, Object],
    default: '',
  },
});
</script>
