<template>
  <div class="about">
    <Header />
    <div class="subtitle"><h6><em>About us</em></h6></div>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
    <Footer class="footer"/>
    </div>
</template>

<script>
  import Header from '../components/layouts/Header.vue';
  import Footer from '../components/layouts/Footer.vue';

  export default {
    components: {
      Header,
      Footer
    }
  }
</script>

<style scoped>
.about {
  background-color: #1E1919;
}
.footer {
  padding: 105px 30px 0 30px;
}
</style>
