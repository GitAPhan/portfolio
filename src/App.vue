<template>
  <div id="app">
    <logo-left class="logo" />
    <about-me class="main"/>
    <logo-right class="logo" />
    <project-section class="main" />
    <footer-section class="main" />
  </div>
</template>

<script>
import FooterSection from '@/components/FooterSection.vue';
import LogoRight from '@/components/LogoRight.vue';
import LogoLeft from '@/components/LogoLeft.vue';
import ProjectSection from '@/components/ProjectSection.vue';
import AboutMe from '@/components/AboutMe.vue';


export default {
  components: {
    FooterSection,
    LogoLeft,
    LogoRight,
    ProjectSection,
    AboutMe,
  },
}
</script>

<style>
* {
  padding: 0px;
  margin: 0px;
}
#app {
  display: grid;
  place-items: center;
  background-color: #464545;
  width: 100vw;
  height: 100vh;
  overflow-x: hidden;
}
.logo {
  height: 100vh;
  background-repeat: no-repeat;
  background-size: 70% 70%;
  width: 100%;
}
.main {
  width: 100%;
}
</style>
