<template>
  <div>
    <section class="section has-text-centered">
      <div class="h2">
        Ресурси
      </div>
      <ol class="h4">
        <!-- <li>
          <a href="https://roamresearch.com/#/app/gkkirilov/graph">
            <u>Мрежата от политици</u>
            <span class="text-dark">*</span>
          </a>
          <p>
            * Всяка прилика с действителни лица и събития е случайна.
          </p>
        </li> -->
        <li class="mb-2">
          <nuxt-link to="/konstitucia">
            <u>КОНСТИТУЦИЯ НА РЕПУБЛИКА БЪЛГАРИЯ</u>
          </nuxt-link>
        </li>
        <li>
          Агрегатор на предизборни обещания:
          <u>
            <a href="https://www.reddit.com/r/te_obeshtaha/">Те Обещаха!</a>
          </u>
        </li>
      </ol>
    </section>
    <div class="h3 text-center mt-5">
      Обратно броене до следващите избори.
      <span>
        <br />
      </span>
    </div>
    <div class="mb-4">
      <no-ssr>
        <flip-countdown deadline="2021-04-04 00:00:00" />
      </no-ssr>
    </div>
    <!-- <div class="text-center">
      <img
        class="img-fluid w-100 w-md-50 rounded"
        src="/TuskAndThePumkin.jpg"
        alt=""
      />
    </div> -->
  </div>
</template>

<script>
import FlipCountdown from 'vue2-flip-countdown';

export default {
  name: 'HomePage',
  components: { FlipCountdown }
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
