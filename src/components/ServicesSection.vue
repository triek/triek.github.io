<template>
  <section class="services section-padding" id="section_3">
    <div class="svg-container">
      <h3 class="about-heading">SERVICES</h3>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-lg-10 col-12 mx-auto">
          <div class="row pt-lg-5">
            <div v-for="service in services" :key="service.title" class="col-lg-6 col-12">
              <ServiceCard
                :title="service.title"
                :price="service.price"
                :description="service.description"
                :icon="service.icon"
                :button-link="service.buttonLink"
                :elevated="service.elevated"
              />
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ServiceCard from './ServiceCard.vue';

const services = [
  {
    title: 'Websites',
    price: '$1,200',
    description:
      'I design websites like this, for commercial and personal uses. I am well-versed in HTML, CSS, JS with Bootstrap and Jquery.',
    icon: 'bi-globe',
    buttonLink: '#',
    elevated: false,
  },
  {
    title: 'Game design',
    price: '$1,800',
    description:
      "I'm familiar with popular game engines like Unity and Godot, using C#, C++, Python and Java. I'm practicing 3D models and visual design.",
    icon: 'bi-lightbulb',
    buttonLink: '#',
    elevated: true,
  },
  {
    title: 'Media specialist',
    price: '$800',
    description:
      'If you need a specialist in digital design, photography, videography, and editing, feel free to discuss with me. I have extensive experience in Adobe tools.',
    icon: 'bi-phone',
    buttonLink: '#',
    elevated: false,
  },
  {
    title: 'Content writing',
    price: '$400',
    description:
      'To make your posts more attractive to future customers, we will work together. I know my way around with catchy and trendy contents.',
    icon: 'bi-google',
    buttonLink: '#',
    elevated: true,
  },
];
</script>
