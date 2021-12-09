<template>
  <div id="app">
    <Header />
    <Hero />
    <Section1 />
    <Section2 />
    <Section3 />
    <Section4 />
    <Section5 />
    <Section6 />
    <Footer />
    

  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Hero from '@/components/Hero.vue';
import Section1 from '@/components/Section1.vue';
import Section2 from '@/components/Section1.vue';
import Section3 from '@/components/Section1.vue';
import Section4 from '@/components/Section1.vue';
import Section5 from '@/components/Section1.vue';
import Section6 from '@/components/Section1.vue';
import Footer from '@/components/Footer.vue';



export default {
  name: 'App',
  components: {
    Header,
    Hero,
    Section1,
    Section2,
    Section3,
    Section4,
    Section5,
    Section6,
    Footer, 
    
  }
}
</script>

<style lang="scss">
@import '@/styles/global.scss';

</style>
