<template>
  <header>
    <nav-landing></nav-landing>
    <div class="header__content">
      <div class="content__text">
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam
          maxime vitae incidunt pariatur, harum optio.
        </p>
        <h2>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eveniet,
          hic.
        </h2>
        <button class="header__button mt-4">Lorem</button>
      </div>
      <div class="content__swiper">
        <div class="w-100 h-100 position-relative">
          <swiper
            :breakpoints="{
              0: {
                slidesPerView: 1,
                spaceBetween: 10,
              },
              870: {
                slidesPerView: 2,
                spaceBetween: 20,
              },
            }"
            navigation
            :autoplay="{ delay: 1000 }"
            :pagination="{ clickable: true }"
            class="slider-header"
          >
            <swiper-slide>
              <img
                class="slider-header__image"
                src="https://dummyimage.com/800x500/4D525B/ffffff"
              />
            </swiper-slide>
            <swiper-slide>
              <img
                class="slider-header__image"
                src="https://dummyimage.com/800x500/4D525B/ffffff"
              />
            </swiper-slide>
            <swiper-slide>
              <img
                class="slider-header__image"
                src="https://dummyimage.com/800x500/4D525B/ffffff"
              />
            </swiper-slide>
            <swiper-slide>
              <img
                class="slider-header__image"
                src="https://dummyimage.com/800x500/4D525B/ffffff"
              />
            </swiper-slide>
          </swiper>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
import SwiperCore, { Pagination, Autoplay } from "swiper";
import { Swiper, SwiperSlide } from "swiper/vue";
import NavLanding from "./NavLanding.vue";

SwiperCore.use([Pagination, Autoplay]);

import "swiper/swiper.scss";
import "swiper/components/pagination/pagination.scss";

export default {
  components: {
    NavLanding,
    Swiper,
    SwiperSlide,
  },
};
</script>
