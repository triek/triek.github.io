<template>
  <section class="projects section-padding" id="section_4">
    <div class="svg-container">
      <h3 class="about-heading">PROJECTS</h3>
    </div>

    <div class="container">
      <div class="row">
        <div class="clearfix"></div>

        <div v-for="project in projects" :key="project.title" class="col-lg-4 col-md-6 col-12">
          <ProjectCard :tag="project.tag" :title="project.title" :link="project.link" :image="project.image" />
        </div>
      </div>
    </div>
  </section>
</template>

<script setup>
import ProjectCard from './ProjectCard.vue';

const projects = [
  {
    tag: 'Web app',
    title: "StuX",
    link: 'https://github.com/triek/stu-x',
    image: '/images/projects/stux.png',
  }, 
  {
    tag: 'Web app',
    title: "Privion",
    link: 'https://github.com/triek/privion',
    image: '/images/projects/privion.png',
  }, 
  {
    tag: 'Web app',
    title: "Tristan's Porfolio",
    link: 'https://github.com/triek/triek.github.io',
    image: '/images/projects/portfolio.png',
  },
  {
    tag: 'Game',
    title: 'Minimos',
    link: 'https://github.com/triek/Minimos',
    image: '/images/projects/minimos_icon.png',
  },
  {
    tag: 'Game',
    title: 'Selaphobia',
    link: 'https://github.com/triek/Selaphobia',
    image: '/images/projects/selaphobia.jpg',
  },
  {
    tag: 'Design',
    title: 'Graphic Design',
    link: 'https://www.behance.net/trietkhuongminh',
    image: '/images/projects/behance.jpg',
  },
];
</script>
