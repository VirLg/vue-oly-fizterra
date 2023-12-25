<template>
  <div class="header_section">
    <ul class="navigate">
      <li class="home navigate_list">Home</li>
      <li class="gallery navigate_list">Gallery</li>
      <li class="contacts navigate_list">Contacts</li>
    </ul>
    <div class="contacts_block">
      <button type="button" class="btn_fb" />

      <button type="button" class="btn_fb telegramm" />
      <button type="button" class="btn_fb instagram" />
      <button type="button" class="btn_fb viber" />
    </div>
  </div>
</template>
<script>
export default {
  name: 'HeaderComponent',
};
</script>
<style>
.header_section {
  outline: 1px solid red;
  width: 1440px;

  align-items: center;
  padding-top: 50px;
  padding-bottom: 50px;
  background-color: green;
}
.navigate {
  display: flex;
  gap: 40px;
  justify-content: center;
  margin: 0;
}
.navigate_list {
  font-size: 34px;
  font-weight: bold;
  color: rgba(255, 255, 255, 0.8);
}
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
  background-image: url('../icons/facebook-svgrepo-com.svg');
  background-size: contain;
  background-repeat: no-repeat;
}
.telegramm::after {
  background-image: url('../icons/telegram.svg');
}

.instagram::after {
  background-image: url('../icons/instagram.svg');
}
.viber::after {
  background-image: url('../icons/viber.svg');
}
.contacts_block {
  display: flex;
  gap: 10px;
  justify-content: center;
  margin-top: 20px;
}
</style>
