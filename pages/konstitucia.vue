<template>
  <div>
    <section class="section has-text-centered">
      <article>
        <h1>{{ page.title }}</h1>
        <nuxt-content :document="page" />
      </article>
    </section>
  </div>
</template>

<script>
export default {
  name: 'Konstitucia',
  async asyncData({ $content }) {
    const page = await $content('konstitucia').fetch();

    return {
      page
    };
  }
};
</script>
<style>
p {
  margin-bottom: 0.5rem;
}
</style>
