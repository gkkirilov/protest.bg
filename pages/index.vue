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
    <iframe src="https://www.strawpoll.me/embed_1/46009045" style="width:680px;height:384px;border:0;">Зарежда...</iframe>
    <!--
    <div class="mb-4">
      <div class="h3 text-center mt-5">
        Обратно броене до следващите избори.
        <div>
          14 ноември 2021г.
        </div>
        <span>
          <br />
        </span>
      </div>
      <client-only>
        <flip-countdown deadline="2021-11-14 00:00:00" />
      </client-only>
    </div>
    -->
    <!-- <div class="h3 text-center mt-4">Браво българи заедно успяхме!</div> -->

    <div class="text-center col-md-6 mx-auto">
      <img
        class="img-fluid w-100 w-md-50 rounded shadow-lg mt-3"
        src="/Flag_of_Bulgaria.svg"
        alt=""
      />
    </div>
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
