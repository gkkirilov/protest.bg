<template>
  <div>
    <section class="section has-text-centered">
      <div class="h2">
        Ресурси
      </div>
      <ol class="h4">
        <li>
          <a href="https://roamresearch.com/#/app/gkkirilov/graph">
            <u>Мрежата от политици</u>
            <span class="text-dark">*</span>
          </a>
        </li>
        <li>
          <nuxt-link to="/konstitucia">
            <u>КОНСТИТУЦИЯ НА РЕПУБЛИКА БЪЛГАРИЯ</u>
            <!-- <b-button type="is-primary is-size-3-tablet"
              >
              </b-button
            > -->
          </nuxt-link>
        </li>
      </ol>
    </section>
    <p>
      * Всяка прилика с действителни лица и събития е случайна.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
};
</script>
