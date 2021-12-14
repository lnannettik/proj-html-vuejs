<template>
  <div id="app">
    <Header />
    <Hero />
    <SectionA />
    <SectionB />
    <SectionC />
    <SectionD />
    <SectionE />
    <SectionF />
    <SectionG />
    <SectionH />
    <Footer />
    

  </div>
</template>

<script>
import Header from "@/components/Header.vue";
import Hero from '@/components/Hero.vue';
import SectionA from '@/components/SectionA.vue';
import SectionB from '@/components/SectionB.vue';
import SectionC from '@/components/SectionC.vue';
import SectionD from '@/components/SectionD.vue';
import SectionE from '@/components/SectionE.vue';
import SectionF from '@/components/SectionF.vue';
import SectionG from '@/components/SectionG.vue';
import SectionH from '@/components/SectionH.vue';
import Footer from '@/components/Footer.vue'


export default {
  name: 'App',
  components: {
    Header,
    Hero,
    SectionA,
    SectionB,
    SectionC,
    SectionD,
    SectionE,
    SectionF,
    SectionG,
    SectionH,
    Footer, 
    
  },
};


</script>

<style lang="scss">
@import '@/styles/global.scss';

</style>
