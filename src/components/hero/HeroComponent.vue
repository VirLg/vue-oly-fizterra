<template>
  <section>
    <div>
      <h1>{{ title }}</h1>
      <img
        src="https://medeja.com.ua/wp-content/uploads/fyz2.jpg"
        alt=""
        width="1300"
        height="500"
      />
    </div>
    <div><ContentHomePage /></div>
    <button type="button">Add Card</button>
  </section>
</template>
<script>
import ContentHomePage from '../content/ContentHomePage.vue';
export default {
  name: 'HeroComponent',
  props: {},
  data() {
    return {
      title: 'Main Page',
    };
  },
  components: {
    ContentHomePage,
  },
};
</script>
