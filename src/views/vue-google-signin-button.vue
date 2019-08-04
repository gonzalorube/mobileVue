<!--<template>
  <div class="container fluid">
    <Header />
    <div class="subtitle"><h6><em>Game Information</em></h6></div>
    <GSignInButton />
    <Footer />
  </div>
</template>

<script>
import Header from '../components/layouts/Header.vue';
import GSignInButton from '../components/vue-google-signin-button';
Vue.use(GSignInButton);

export default {
  name: 'SignIn',
  components: {
    Header,
    GSignInButton,
    Footer
  }
}
</script>

<style lang="css" scoped>
</style>
