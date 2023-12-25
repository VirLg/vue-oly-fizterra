<template>
  <div class="content">
    <h2 class="content_title">{{ title }}</h2>
    <p class="content_text">{{ text }}</p>
  </div>
</template>
<script>
export default {
  name: 'ContentHomePage',
  props: {},
  data() {
    return {
      title: 'Кабинет физиотерапии ',
      text: 'Массаж в свою ',
    };
  },
};
</script>
