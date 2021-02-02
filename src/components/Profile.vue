<template>
  <div 
    id="profile" 
  >
    <section
      class="flex flex-col justify-center items-center h-auto w-auto sm:flex-row"
    >
      <div class="avatar mr-6 mb-6 sm:mb-0">
        <img 
          class="rounded-full h-64 w-64"
          src="../images/avatar.jpg" 
          alt="avatar-image"
        >
      </div>
      <div class="about flex flex-col justify-center items-center sm:items-start">
        <h2 
          class="flex flex-row text-3xl text-center mb-3 font-normal text-black text-4xl"
        >
          {{ fullName }}
        </h2>
        <p 
          class="mb-3 text-lg"
        >
          <span>&#128187; </span>{{ position }}
        </p>
         <p
          class="mb-3 text-base"
        >
          <span>&#128222;</span>{{ contact }}
        </p>
        <p
          class="mb-3 text-base"
        >
          <span>&#128205;</span>{{ location }}
        </p>
        <div class="skills mb-3">
          <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            html
          </span>
          <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            css
          </span>
          <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            javascript
          </span>
           <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            Angular
          </span>
          <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            Typescript
          </span>
           <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            Reactjs
          </span>
          <span 
            class="inline-block bg-purple-200 rounded-sm px-2 py-1 text-sm font-normal mr-2 mb-2 last:mr-0"
          >
            vue.js
          </span>
        </div>
        <div
          class="contact-links flex flex-row justify-center w-full sm:justify-start"
        >
          <a href="https://www.linkedin.com/in/namrata-chaudhari/" target="_blank" class="mr-2 w-8">
            <img src="../images/logo/linkedin-logo.png" alt="linkedin-logo">
          </a>
          <a href="https://github.com/namrata9503?tab=repositories" target="_blank" class="mr-2 w-8">
            <img src="../images/logo/github-logo-icon.png" alt="github-logo">
          </a>
          
        </div>
      </div>
    </section>
  </div>
</template>

<script>
  export default {
    name: 'Profile',
    data () {
      return {
      fullName: 'Namrata Chaudhari',
      position: 'Frontend Developer',
      contact: 'nam9503@gmail.com | +31 6 22335523',
      location: 'The Netherlands'
      }
    }
  }
</script>

<style scoped>
</style>