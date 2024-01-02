<template lang="">
  <li>
    <div>
      <p>{{ massag_data.name }}</p>
      <p>{{ massag_data.date }}</p>
      <p>{{ massag_data.price }}</p>
    </div>
  </li>
</template>
<script>
export default {
  name: 'ContentHomePageItem',
  props: {
    massag_data: {
      type: Object,
      default() {
        return {};
      },
    },
  },
};
</script>
<style lang=""></style>
