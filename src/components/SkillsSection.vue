<template>
  <section class="services section-padding" id="section_5">
    <div class="svg-container">
      <h3 class="about-heading">SKILLS</h3>
    </div>

    <div class="container">
      <div class="row">
        <div class="col-12 mx-auto">
          <div class="row pt-lg-5">
            <div v-for="(skill, index) in skills" :key="skill.name" class="col-lg-4 col-12">
              <Card :customClass="['services-thumb', { 'services-thumb-up': index % 2 === 1 }]" class="pb-5">
                <div class="d-flex align-items-center border-bottom mb-4 pb-3">
                  <i :class="['bi', skill.icon, 'me-3 text-danger fs-1']"></i>
                  <h3 class="mb-0 ms-3">{{ skill.name }}</h3>
                </div>

                <p class="mb-3">{{ skill.description }}</p>

                <div class="d-flex flex-wrap gap-2 mb-4">
                  <span v-for="tag in skill.tags" :key="tag" class="badge bg-light text-dark border">
                    {{ tag }}
                  </span>
                </div>
              </Card>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import Card from './Card.vue';

const skills = [
  {
    name: 'Front-end Development',
    description: 'Vue 3 with Vite, reusable component patterns, responsive layouts, and modern JavaScript fundamentals.',
    icon: 'bi-laptop',
    tags: ['Vue 3', 'TypeScript', 'Vite', 'SPA patterns'],
  },
  {
    name: 'Styling & UI Systems',
    description: 'Responsive layouts with Tailwind CSS and Bootstrap, plus reusable design systems.',
    icon: 'bi-palette',
    level: 'Advanced',
    tags: ['Tailwind CSS', 'Bootstrap', 'Design tokens', 'Responsive'],
  },
  {
    name: 'State & Data Layer',
    description: 'REST integrations, composables, and lightweight state management strategies.',
    icon: 'bi-diagram-3',
    level: 'Advanced',
    tags: ['REST APIs', 'Composables', 'State mgmt', 'Caching'],
  },
  {
    name: 'Testing & Quality',
    description: 'Unit testing habits with Vitest and Vue Test Utils alongside accessibility checks.',
    icon: 'bi-shield-check',
    level: 'Proficient',
    tags: ['Vitest', 'Vue Test Utils', 'Accessibility', 'Linting'],
  },
  {
    name: 'Tooling & DevOps',
    description: 'Git for version control, automated formatting, and fast feedback builds with Vite.',
    icon: 'bi-gear',
    level: 'Proficient',
    tags: ['Git', 'CI-ready', 'Prettier/ESLint', 'Fast builds'],
  },
  {
    name: 'Content & Media',
    description: 'Copywriting, media editing, and asset optimization to keep pages lightweight.',
    icon: 'bi-pen',
    level: 'Proficient',
    tags: ['Copywriting', 'Media editing', 'Optimization', 'SEO basics'],
  },
];
</script>
