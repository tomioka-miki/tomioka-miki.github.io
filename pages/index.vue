<template>
  <div class="container">
    <AboutMe/>
    <Skills/>
    <Work/>
  </div>
</template>

<script>
  import AboutMe from '~/pages/AboutMe';
  import Skills from '~/pages/Skills';
  import Work from '~/pages/Work';

  export default {
    components: {
      AboutMe,
      Skills,
      Work,
    }
  }
</script>

<style>
</style>
