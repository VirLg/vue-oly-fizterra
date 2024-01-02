<template>
  <section>
    <div style="margin-top: 20px">
      <img
        src="https://medeja.com.ua/wp-content/uploads/fyz2.jpg"
        alt=""
        width="1300"
        height="500"
      />
    </div>
    <div>
      <ContentHomePage />
    </div>
    <button type="button">Add Card</button>
  </section>
</template>
<script>
import ContentHomePage from '../content/ContentHomePage.vue';
export default {
  name: 'HeroComponent',
  props: {},
  data() {
    return {};
  },
  components: {
    ContentHomePage,
  },
  methods: {},
};
</script>
