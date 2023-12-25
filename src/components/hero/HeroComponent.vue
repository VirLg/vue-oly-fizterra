<template>
  <section>
    <div>
      <h1>{{ title }}</h1>
      <img
        src="https://medeja.com.ua/wp-content/uploads/fyz2.jpg"
        alt=""
        width="800"
        height="300"
      />
      <button type="button">Add Card</button>
    </div>
  </section>
</template>
<script>
export default {
  name: 'HeroComponent',
  props: {},
  data() {
    return {
      title: 'Main Page',
    };
  },
};
</script>
