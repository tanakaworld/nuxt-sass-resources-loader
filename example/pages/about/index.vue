<template>
  <section class="container">
    <div>
      <app-logo/>
      <h1 class="title">
        About
      </h1>
      <div class="links">
        <nuxt-link to="/">Home</nuxt-link>
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
  @import "@/assets/styles/variables.sass"

  .container
    background-color: $color-title-home
</style>
