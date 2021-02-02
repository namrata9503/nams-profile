<template>
  <div id="projects">
    <section>
      <div class="grid grid-cols-1 gap-8 mx-10 sm:grid-cols-3">
        <div 
          v-for="project in projects" :key="project.name"
        >
          <Project v-bind:project="project" class="project"/>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import {projects} from '../database/projects'
import Project from './Project.vue'

export default {
  name: 'Projects',
  data () {
    return {
      projects: projects
    }
  },
  components: {
    Project
  }
}
</script>

<style scoped>

.project{
box-shadow: 3px 3px 5px 6px #ccc;
}

</style>