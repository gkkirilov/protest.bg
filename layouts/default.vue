<template>
  <div>
    <b-navbar type="dark" variant="primary">
      <nuxt-link to="/">
        <b-navbar-brand tag="h1" href="/"
          ><h1 class="h3">Протест.бг</h1></b-navbar-brand
        >
      </nuxt-link>
    </b-navbar>

    <section class="main-content columns">
      <div class="container column">
        <nuxt />
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          title: 'Home',
          icon: 'home',
          to: { name: 'index' }
        },
        {
          title: 'Inspire',
          icon: 'lightbulb',
          to: { name: 'inspire' }
        }
      ]
    };
  }
};
</script>
