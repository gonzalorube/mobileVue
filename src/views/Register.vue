<template>
  <div class="container-fluid">
    <Header />
    <div class="subtitle"><h6><em>Register</em></h6></div>
    <h3>Not registered already?</h3>
    <p>If you're not already registered, you can do it as follows</p>
    <Footer />
  </div>
</template>

<script>
import Header from '../components/layouts/Header.vue';
import Footer from '../components/layouts/Footer.vue';

export default {
  name: 'Register',
  components: {
    Header,
    Footer
  }
}
</script>

<style lang="css" scoped>
h3 {
  color: #FFFFFF;
  font-size: 20px;
  margin-bottom: 10px;
}
p {
  color: #FFFFFF;
  font-size: 10px;
}
</style>
