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
                  <i :class="['bi', skill.icon, 'text-danger fs-1']"></i>
                  <h3 class="mb-0 ms-3 fs-3">{{ skill.name }}</h3>
                </div>

                <p class="mb-3">{{ skill.description }}</p>

                <div class="d-flex flex-wrap gap-2 mb-4 fs-5">
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
    tags: ['Vue 3', 'TypeScript', 'Vite', 'Component patterns'],
  },
  {
    name: 'Styling & UI Systems',
    description: 'Clean interfaces with Tailwind CSS and Bootstrap, plus UI flows focused on clarity and simplicity.',
    icon: 'bi-palette',
    tags: ['Tailwind CSS', 'Bootstrap', 'Responsive', 'UI layouts'],
  },
  {
    name: 'Quality & Debugging',
    description: 'Practical debugging, code cleanup, responsive testing, and improving UI behavior through iteration.',
    icon: 'bi-shield-check',
    tags: ['Debugging', 'Accessibility basics', 'Responsive testing'],
  },
  {
    name: 'State & Data Layer',
    description: 'Basic REST integrations, composables, and lightweight state management for small to medium applications.',
    icon: 'bi-diagram-3',
    tags: ['REST APIs', 'Composables', 'State mgmt'],
  },
  {
    name: 'Tooling & Dev Tools',
    description: 'Git for version control, GitHub workflows, fast builds with Vite, and efficient CLI-based development.',
    icon: 'bi-gear',
    tags: ['Git', 'GitHub', 'VS Code', 'CLI tools'],
  },
  {
    name: 'Design & Media',
    description: 'Poster design, product mockups, UI concepts, and asset preparation for apps and social content.',
    icon: 'bi-pencil',
    tags: ['Poster design', 'Mockups', 'UI design', 'Basic editing'],
  },
];
</script>
