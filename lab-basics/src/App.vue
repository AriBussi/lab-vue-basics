<script>
import Navbar from './components/TheNavbar.vue';
import Footer from './components/TheFooter.vue';
import PostList from './components/PostList.vue';

export default {
  name: 'App',
  components: {
    Navbar,
    Footer,
    PostList
}
}
</script>

<template>
  <Navbar />
  <PostList />
  <Footer />
</template>

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
