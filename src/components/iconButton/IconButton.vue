<template>
  <div>
    <button>children</button>
    <button type="button" class="btn_fb" />
  </div>
</template>
<script>
export default {
  name: 'IconButton',

  metods: {},
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
  background-image: url('');
  background-size: contain;
  background-repeat: no-repeat;
}
</style>
