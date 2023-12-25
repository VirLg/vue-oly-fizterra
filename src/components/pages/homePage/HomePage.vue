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
          <button type="button">Viber</button>
          <button type="button">Telegramm</button>
          <button type="button">Insta</button>
          <button type="button">Linkedin</button>
        </div>
      </div>
    </section>
    <section>
      <div><HeroComponent /></div>
    </section>
  </div>
</template>
<script>
import HeroComponent from '../../hero/HeroComponent.vue';
export default {
  name: 'HomePage',
  components: {
    HeroComponent,
  },
};
</script>
