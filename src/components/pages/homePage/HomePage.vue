<template>
  <div>
    <section>
      <div class="header">
        <div class="logo"></div>
        <ul class="navigate">
          <li class="home">Home</li>
          <li class="gallery">Gallery</li>
          <li class="contacts">Contacts</li>
        </ul>
        <div class="contacts">
          <button type="button" class="btn_fb" />
          <IconButton children="children" />
          <button type="button">Telegramm</button>
          <button type="button">Insta</button>
          <button type="button">Linkedin</button>
        </div>
      </div>
    </section>
    <section>
      <div><HeroComponent /></div>
    </section>
    <section>
      <div><ContentHomePage /></div>
    </section>
    <section>
      <div><FooterComponent /></div>
    </section>
  </div>
</template>
<script>
import HeroComponent from '../../hero/HeroComponent.vue';
import ContentHomePage from '../../content/ContentHomePage.vue';
import FooterComponent from '../../footer/FooterComponent.vue';
import IconButton from '../../iconButton/IconButton.vue';
export default {
  name: 'HomePage',
  props: {},
  data() {
    return {};
  },
  components: {
    HeroComponent,
    ContentHomePage,
    FooterComponent,
    IconButton,
  },
};
</script>
<style>
.btn_fb {
  width: 80px;
  height: 80px;
  display: flex;
}
.btn_fb:hover,
.btn_fb:focus {
  background-color: teal;
}

.btn_fb::after {
  content: '';
  width: 80px;
  height: 80px;
  background-image: url('../../icons/facebook-svgrepo-com.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
</style>
