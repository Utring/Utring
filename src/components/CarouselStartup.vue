<template>
  <div
    class="brand-logo-slider-area bg-gray section-space--pt_100 section-space--pb_60 startup-carousel"
  >
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="section-title text-center section-space--mb_30">
            <h2 class="font-weight--bold mb-15 wow move-up">
              Una empresa confiable de primera
            </h2>
            <span class="section-text wow move-up"
              >Brindamos los mejores servicios para el diseño y codificación de
              aplicaciones.</span
            >
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <div class="brand-logo-slider__container-area">
            <div class="swiper-container brand-logo-slider__container">
              <div class="swiper-wrapper brand-logo-slider__wrapper">
                <swiper :options="swiperOption">
                  <div class="swiper-slide">
                    <div class="brand-logo mb-0 wow move-up">
                      <a href="https://parquesoft.com/" target="_blank">
                        <img
                          src="../assets/img/brand/parquesoft.png"
                          class="img-fluid"
                          alt="brand logo"
                        />
                      </a>
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="brand-logo mb-0 wow move-up">
                      <a href="https://eagent.energy/" target="_blank">
                        <img
                          src="../assets/img/brand/eagent.png"
                          class="img-fluid"
                          alt="brand logo"
                        />
                      </a>
                    </div>
                  </div>
                  <div class="swiper-slide">
                    <div class="brand-logo mb-0 wow move-up">
                      <a href="http://bluearas.com" target="_blank">
                        <img
                          src="../assets/img/brand/blueras.png"
                          class="img-fluid"
                          alt="brand logo"
                        />
                      </a>
                    </div>
                  </div>
                </swiper>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CarouselStartup",
  data() {
    return {
      swiperOption: {
        speed: 800,
        loop: true,
        autoplay: true,
        slidesPerView: 5,
        spaceBetween: 30,
        breakpoints: {
          991: {
            slidesPerView: 4,
          },

          767: {
            slidesPerView: 3,
          },
          575: {
            slidesPerView: 2,
          },
        },
      },
    };
  },
};
</script>