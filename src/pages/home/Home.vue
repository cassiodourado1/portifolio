<template>
  <div class="home">
    <header-bar/>
    <div class="container-home">
      <h1>Cassio Dourado</h1>
      <about-me/>
      <portifolio-grid/>
    </div>
  </div>
</template>

<script>
import HeaderBar from '@/components/headerbar/Header';
import PortifolioGrid from './components/portifolioGrid/portifolioGrid';
import AboutMe from './components/aboutMe/aboutMe';

export default {
  name: 'Home',

  components: {
    HeaderBar,
    AboutMe,
    PortifolioGrid,
  },

  data() {
    return {};
  },

  methods: {},
};
</script>

<style lang='stylus' src='./Home.styl' scoped />
