<template>
<HomePage/>
<GallaryPage/>
<ContactsPage/>
</template>

<script>
import HomePage from './components/pages/homePage/HomePage.vue'
import GallaryPage from './components/pages/gallery/GallaryPage.vue'
import ContactsPage from './components/pages/contacts/ContactsPage.vue'
export default {
  name: 'App',
  data() {
    return {
   
    };
  },
  components: {
    HomePage,
    GallaryPage,
    ContactsPage,
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
