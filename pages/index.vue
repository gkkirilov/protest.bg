<template>
  <div>
    <section class="section has-text-centered text-center">
      <!-- <div class="h2">Ресурси</div> -->
      <div class="h4">
        <!-- <li>
          <a href="https://roamresearch.com/#/app/gkkirilov/graph">
            <u>Мрежата от политици</u>
            <span class="text-dark">*</span>
          </a>
          <p>
            * Всяка прилика с действителни лица и събития е случайна.
          </p>
        </li> -->
        <div class="my-2">
          <nuxt-link to="/konstitucia">
            <u>КОНСТИТУЦИЯ НА РЕПУБЛИКА БЪЛГАРИЯ</u>
          </nuxt-link>
        </div>
      </div>
    </section>
    <div class="h3 text-center mt-4">Браво българи заедно успяхме!</div>

    <div class="text-center">
      <img
        class="img-fluid w-100 w-md-50 rounded shadow-lg mt-3"
        src="/Flag_of_Bulgaria.svg"
        alt=""
      />
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomePage'
};
</script>
<style>
.flip-card__top {
  color: white !important;
}
.flip-card__bottom {
  color: white !important;
}
.flip-card__top-bottom {
  color: white !important;
}
.flip-card__back-bottom {
  color: white !important;
}
.flip-card__back::before {
  color: white !important;
}
</style>
