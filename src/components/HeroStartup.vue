<template>
    <section class="hero-branding bg-cover" :style="bgImg" id="home">
        <div class="container-fluid container-fluid--cp-150">
            <div class="row hero-startup">
                <div class="col-md-6">
                    <div class="hero-content">
                        <h2 class="h1 hero-content-title">Developing Impact</h2>
                        <h6 class="hero-content-subtitle mt-20">Somos una empresa de consultoría de software que diseña, desarrolla e implementa soluciones de software personalizadas para organizaciones que desean generar un impacto a través de la tecnología.</h6>
                        <div class="slider-button mt-30">
                            <router-link to="" class="btn btn--purple">Empieza!</router-link>
                            <h6 class="sub-heading">
                                Tienes inquietudes? 
                                <router-link to="" class="hover-style-link hover-style-link--green">Consulta con nuestro equipo de trabajo</router-link>
                            </h6>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 align-self-end">
                    <div class="startup-thumb">
                        <img src="../assets/img/hero/startup/startup-thumb-2.png" class="img-fluid" alt="startup-thumb">
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data (){
            return {
                bgImg: {
                    backgroundImage: `url(${require('../assets/img/hero/startup/startup-bg-2.png')})`
                },
            }
        }
    }
</script>

<style lang="scss" scoped>
    @import '../assets/scss/variabls.scss';
    @import '../assets/scss/elements/hero-branding.scss';
    
    .hero-branding {
        // responsive
        @media #{$large-mobile}{
            height: 950px;
        }
    }
    .hero-startup {
        align-items: center;
        display: flex;
        height: 100vh;
        .startup-thumb {
            bottom: -32px;
            position: relative;
            z-index: 1;
            // responsive
            @media #{$tablet-device}{
                bottom: -15px;
            }
        }
    }
        .hero-content {
            // responsive
            @media #{$tablet-device}{
                width: 100%;
            }
            &-title,
            &-subtitle {
                color: $white;
            }
            .slider-button {
                display: flex;
                align-items: center;
                // responsive
                @media #{$tablet-device, $extra-small-mobile}{
                    display: block;
                }
            }
            .sub-heading {
                font-size: 15px;
                color: $white;
                padding-left: 20px;
                // responsive
                @media #{$tablet-device, $extra-small-mobile}{
                    padding-left: 0;
                    padding-top: 15px;
                }
            }
        }
</style>
