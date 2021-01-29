<template>
    <div class="footer-area-wrapper" :class="FooterStyle">
        <div class="footer-area section-space--ptb_90">
            <div class="container">
                <div class="row footer-widget-wrapper">
                    <div class="col-lg-4 col-md-6 footer-widget">
                        <div class="footer-widget__logo mb-30">
                            <router-link to="/">
                                <img src="../assets/img/logo/logo-dark-1.png" class="img-fluid logo-dark" alt="logo">
                                <img src="../assets/img/logo/light-logo-1.png" class="img-fluid logo-light" alt="logo">
                            </router-link>
                        </div>
                        <ul class="footer-widget__list">
                            <li>Calle 4 # 34 29, San Fernando, Cali Valle Colombia</li>
                            <li>
                                <a href="mailto:contact@aeroland.com" class="hover-style-link">contacto@utring.com</a>
                            </li>
                            <li>
                                <a href="tel:(+68)122109876" class="hover-style-link">(+57)300 0000000</a>
                            </li>
                            <li>
                                <a href="www.website.com" target="_blank" class="hover-style-link hover-style-link--green">www.website.com</a>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 footer-widget">
                        <h6 class="footer-widget__title mb-20">Quienes somos</h6>
                        <ul class="footer-widget__list">
                            <li>
                                <router-link to="/" class="hover-style-link">Sobre nosotros</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Antes de que te vayas</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Registro en Linea</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Preguntas más frecuentes</router-link>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-2 col-md-6 footer-widget">
                        <h6 class="footer-widget__title mb-20">Enlaces Rápidos</h6>
                        <ul class="footer-widget__list">
                            <li>
                                <router-link to="/" class="hover-style-link">Nuestras Sedes</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Condiciones de Pago</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Políticas de Privacidad</router-link>
                            </li>
                            <li>
                                <router-link to="/" class="hover-style-link">Dónde Encontrarnos</router-link>
                            </li>
                        </ul>
                    </div>
                    <div class="col-lg-3 col-md-6 offset-lg-1 footer-widget">
                        <div class="twitter-feed-slider">
                            <div class="swiper-container twitter-feed-slider__container">
                                <div class="swiper-wrapper twitter-feed-slider__wrapper">
                                    <div class="swiper-slide twitter-feed-slider__single">
                                        <div class="tweet">
                                            <div class="tweet__text">
                                                Si el código y los comentarios no coinciden, posiblemente ambos sean incorrectos. – Norm Schryer
                                                <!-- <a href="https://t.co/jSRMsZAdPW" target="_blank">https://t.co/jSRMsZAdPW</a>
                                                <a href="https://t.co/2iDReuyPMt" target="_blank">https://t.co/2iDReuyPMt</a> -->
                                            </div>
                                            <div class="tweet__info">
                                                <h6 class="tweet__heading">Utring</h6>
                                                <span class="tweet__date">Enero 28, 2021</span>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer-copyright-area border-top section-space--ptb_30">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-md-6 text-center text-md-left">
                        <span class="copyright-text">© 2021 Utring. All Rights Reserved.</span>
                    </div>
                    <div class="col-md-6 text-center text-md-right">
                        <ul class="list ht-social-networks solid-rounded-icon">
                            <li class="item">
                                <a href="https://www.facebook.com/" target="_blank" class="social-link"> <i class="fab fa-facebook social-link-icon"></i> </a>
                            </li>
                            <li class="item">
                                <a href="https://twitter.com/" target="_blank" class="social-link"> <i class="fab fa-twitter social-link-icon"></i> </a>
                            </li>
                            <li class="item">
                                <a href="https://www.instagram.com/" target="_blank" class="social-link"> <i class="fab fa-instagram social-link-icon"></i> </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'FooterMain',
        props: ["FooterStyle"]
    }
</script>