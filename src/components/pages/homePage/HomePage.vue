<template>
  <div class="">
    <section class="section">
      <div class="logo"></div>

      <div><HeaderComponent /></div>
    </section>
    <section section class="section">
      <div><HeroComponent /></div>
    </section>
    <section section class="section">
      <div><ContentHomePage /></div>
    </section>
    <section section class="section">
      <div><FooterComponent /></div>
    </section>
  </div>
</template>
<script>
import HeaderComponent from '../../header/HeaderComponent.vue';
import HeroComponent from '../../hero/HeroComponent.vue';
import ContentHomePage from '../../content/ContentHomePage.vue';
import FooterComponent from '../../footer/FooterComponent.vue';

export default {
  name: 'HomePage',
  props: {},
  data() {
    return {};
  },
  components: {
    HeaderComponent,
    HeroComponent,
    ContentHomePage,
    FooterComponent,
  },
};
</script>
<style>
.section {
  width: 1440px;
  margin-left: auto;
  margin-right: auto;
}
</style>
