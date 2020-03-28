<template>
  <div>
    <Header/>
    <main class="contents">
      <nuxt/>
    </main>
    <Scrolltop/>
    <Footer/>
  </div>
</template>

<script>
  import Header from '~/components/layouts/Header';
  import Footer from '~/components/layouts/Footer';
  import Scrolltop from '~/components/ui/Scrolltop';

  export default {
    components: {
      Header,
      Footer,
      Scrolltop,
    }
  }
</script>>