<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        Home
      </h1>
      <div class="links">
        <nuxt-link to="/about">About</nuxt-link>
      </div>
    </div>
  </section>
</template>

<script>
  import AppLogo from '~/components/AppLogo.vue';

  export default {
    components: {
      AppLogo,
    },
  };
</script>

<style scoped lang="sass">
  .container
    background-color: $color-title-about
</style>
