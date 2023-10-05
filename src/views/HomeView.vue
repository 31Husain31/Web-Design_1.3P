<template>
  <section class="portfolio-home">
    <header class="portfolio-header">
      <h1>Husainuddin Mohammed</h1>
      <p>Student of Web Design at Deakin ^^</p>
    </header>

    <section class="portfolio-intro">
      <p>
        Greetings and Welcome everyone! I present you my portfolio which consists of everything about me and my projects so that you may get to knwo me better ^^
      </p>
    </section>

    <section class="portfolio-projects">
      <h2>My Achievements✨</h2>
      <div class="projects-grid">
        <div class="project-card" v-for="project in projects" :key="project.id">
          <img :src="project.image" :alt="project.name" />
          <h3>{{ project.name }}</h3>
          <p>{{ project.description }}</p>
        </div>
      </div>
    </section>

    <footer class="portfolio-footer">
      <p>Thank you for visiting! Let's <a href="mailto:flamesofkindness@gmail.com">connect</a>.</p>
    </footer>
  </section>
</template>

<script setup>
import { ref } from 'vue';

import projectImage1 from '../assets/images/Game_Final.png';
import projectImage2 from '../assets/images/Game_Part2.png';

const projects = ref([
  {
    id: 1,
    name: 'Unfinished Space-Rocket-Shooter',
    description: 'This is when I was creating a new game project from the very begening and built up the entire code. This was done using c++',
    image: projectImage2
  },
  {
    id: 2,
    name: 'Finished Space-Rocket-Shooter',
    description: 'This is a screenshot of my Game Over page after I completed making the entire Space-Rocket-Shooting Game',
    image: projectImage1
  },
  // ... add more projects as needed
]);
</script>

<style scoped>
.portfolio-home {
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

.portfolio-header {
  text-align: center;
  margin-bottom: 50px;
}

.portfolio-header h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

.portfolio-intro {
  text-align: center;
  margin-bottom: 50px;
}

.portfolio-projects {
  margin-bottom: 50px;
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 20px;
}

.project-card {
  border: 1px solid #14f000;
  border-radius: 30px;
  overflow: hidden;
}

.project-card img {
  width: 100%;
  height: auto;
}

.project-card h3 {
  text-align: center;
  padding: 10px 0;
}

.portfolio-footer {
  text-align: center;
}
</style>
