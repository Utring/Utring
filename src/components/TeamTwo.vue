<template>
    <div class="row">
        <div class="col-lg-12">
            <div class="section-title text-center section-space--mb_60">
                <h2 class="font-weight--light text-white mb-15 wow move-up">Nuestros expertos</h2>
                <span class="section-text text-white wow move-up">Somos un equipo multidisciplinario de profesionales expertos en desarrollo de Software, IoT y Analítica Avanzada. </span>
            </div>
        </div>
        <div class="col-lg-12">
            <div class="swiper-container team-slider__container">
                <swiper :options="swiperOption">
                    <div class="swiper-slide">
                        <div class="grid-item wow move-up">
                            <!-- ht-team-member Start -->
                            <div class="ht-team-member text-center">
                                <div class="ht-team-member--inner">
                                    <!-- team-image Start -->
                                    <div class="team-image">
                                        <img class="img-fluid" src="https://media-exp1.licdn.com/dms/image/C5603AQG6skSx0QlPAg/profile-displayphoto-shrink_200_200/0/1599051629416?e=1617235200&v=beta&t=iPIT3iAOH5_ADmmtsyzUM_We_PfdynLfnmZAQ5PpkqA" alt="avatar 01" width="150">
                                    </div>
                                    <!-- team-image End -->
                                    <!-- team-info Start -->
                                    <div class="team-info text-center">
                                        <h5 class="name">Laura Orozco</h5>

                                        <div class="position">Statistician | Data Scientist</div>

                                        <div class="social-networks-rounded mt-10">
                                            <ul class="list ht-social-networks solid-rounded-icon">
                                                <!-- <li class="item">
                                                    <a target="_blank" href="https://www.facebook.com/laura.orozco.507027" class="social-link hint--bounce hint--top  hint--primary" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://twitter.com/LauraOrozcoC" class="social-link hint--bounce hint--top hint--primary" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                                                </li> -->
                                                <!-- <li class="item">
                                                    <a target="_blank" href="#" class="social-link hint--bounce hint--top hint--primary" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                                                </li>  -->
                                                <li class="item">
                                                    <a target="_blank" href="https://github.com/LauraOrozco" class="social-link hint--bounce hint--top hint--primary" aria-label="GitHub"><i class="fab fa-github"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://www.linkedin.com/in/laura-orozco-32304bbb/" class="social-link hint--bounce hint--top hint--primary" aria-label="Linkedin"><i class="fab fa-linkedin"></i></a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                    <!-- team-info End -->
                                </div>
                            </div>
                            <!-- ht-team-member End -->
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="grid-item wow move-up">
                            <!-- ht-team-member Start -->
                            <div class="ht-team-member text-center">
                                <div class="ht-team-member--inner">
                                    <!-- team-image Start -->
                                    <div class="team-image">
                                        <img class="img-fluid" src="https://media-exp1.licdn.com/dms/image/C4E03AQExq8BqpTMDew/profile-displayphoto-shrink_200_200/0/1608417257605?e=1617235200&v=beta&t=ySKHpo6-yHfiV0Ip8TxxkrvVyicQgwvvXkgpOsL6cTY" alt="avatar 02" width="150">
                                    </div>
                                    <!-- team-image End -->
                                    <!-- team-info Start -->
                                    <div class="team-info text-center">
                                        <h5 class="name">Carlos Tovar</h5>

                                        <div class="position">Fullstack Software Developer</div>

                                        <div class="social-networks-rounded mt-10">
                                            <ul class="list ht-social-networks solid-rounded-icon">
                                                <!-- <li class="item">
                                                    <a target="_blank" href="https://www.facebook.com/almendro.avellano" class="social-link hint--bounce hint--top  hint--primary" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                                                </li> -->
                                                <!-- <li class="item">
                                                    <a target="_blank" href="#" class="social-link hint--bounce hint--top hint--primary" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="#" class="social-link hint--bounce hint--top hint--primary" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                                                </li> -->
                                                <li class="item">
                                                    <a target="_blank" href="https://github.com/cartovarc" class="social-link hint--bounce hint--top hint--primary" aria-label="GitHub"><i class="fab fa-github"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://www.linkedin.com/in/carlos-fernando-tovar-ceron/" class="social-link hint--bounce hint--top hint--primary" aria-label="Linkedin"><i class="fab fa-linkedin"></i></a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                    <!-- team-info End -->
                                </div>
                            </div>
                            <!-- ht-team-member End -->
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="grid-item wow move-up">
                            <div class="ht-team-member text-center">
                                <div class="ht-team-member--inner">
                                    <div class="team-image">
                                        <img class="img-fluid" src="https://media-exp1.licdn.com/dms/image/C5603AQFIrP3vUsiE3w/profile-displayphoto-shrink_200_200/0/1517403667327?e=1617235200&v=beta&t=JJ-vCDMVAUb1XKWoMlMe7BMJpIzO4aEqRljgDZmBbEk" alt="avatar 03" width="150">
                                    </div>
                                    <div class="team-info text-center">
                                        <h5 class="name">Nestor Cardona</h5>

                                        <div class="position">Embedded Software Developer</div>

                                        <div class="social-networks-rounded mt-10">
                                            <ul class="list ht-social-networks solid-rounded-icon">
                                                <!-- <li class="item">
                                                    <a target="_blank" href="#" class="social-link hint--bounce hint--top  hint--primary" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="#" class="social-link hint--bounce hint--top hint--primary" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                                                </li> -->
                                                <li class="item">
                                                    <a target="_blank" href="https://github.com/NestorKrdona" class="social-link hint--bounce hint--top hint--primary" aria-label="GitHub"><i class="fab fa-github"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://www.linkedin.com/in/nestor-cardona-442b26107/" class="social-link hint--bounce hint--top hint--primary" aria-label="Linkedin"><i class="fab fa-linkedin"></i></a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="swiper-slide">
                        <div class="grid-item wow move-up">
                            <div class="ht-team-member text-center">
                                <div class="ht-team-member--inner">
                                    <div class="team-image">
                                        <img class="img-fluid" src="https://media-exp1.licdn.com/dms/image/C4E03AQFb8gWcj62ppg/profile-displayphoto-shrink_200_200/0/1611848444522?e=1617235200&v=beta&t=3jDHQeCnTaaAnnbp2XdPa_qZvAOOYRyeL85rrsoSfzg" alt="avatar 04" width="150">
                                    </div>
                                    <div class="team-info text-center">
                                        <h5 class="name">Diego Calderon</h5>

                                        <div class="position">Frontend Software Developer</div>

                                        <div class="social-networks-rounded mt-10">
                                            <ul class="list ht-social-networks solid-rounded-icon">
                                                <!-- <li class="item">
                                                    <a target="_blank" href="https://www.facebook.com/Dariantt" class="social-link hint--bounce hint--top  hint--primary" aria-label="Facebook"><i class="fab fa-facebook"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://twitter.com/DiegoCalderonA2" class="social-link hint--bounce hint--top hint--primary" aria-label="Twitter"><i class="fab fa-twitter"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://www.instagram.com/diegocalderonandrade/" class="social-link hint--bounce hint--top hint--primary" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                                                </li> -->
                                                <li class="item">
                                                    <a target="_blank" href="https://github.com/dcaland" class="social-link hint--bounce hint--top hint--primary" aria-label="GitHub"><i class="fab fa-github"></i></a>
                                                </li>
                                                <li class="item">
                                                    <a target="_blank" href="https://www.linkedin.com/in/diego-fernando-calderon-andrade-277b0410a/" class="social-link hint--bounce hint--top hint--primary" aria-label="Linkedin"><i class="fab fa-linkedin"></i></a>
                                                </li>
                                            </ul>
                                        </div>
                                    </div>
                                    <!-- team-info End -->
                                </div>
                            </div>
                            <!-- ht-team-member End -->
                        </div>
                    </div> 
                </swiper>
                <!-- Add Arrows -->
                <div class="swiper-pagination swiper-pagination-2 section-space--mt_50"></div>
            </div>
        </div>
    </div>
                
</template>

<script>
    export default {
        name: 'TeamTwo',
        data () {
            return {
                swiperOption: {
                    speed: 800,
                    loop: true,
                    slidesPerView: 4,
                    spaceBetween : 10,
                    pagination: {
                        el: '.swiper-pagination',
                        clickable: true
                    },
                     breakpoints: {
                        1499:{
                            slidesPerView : 4
                        },

                        991:{
                            slidesPerView : 3

                        },
                        767:{
                            slidesPerView : 2

                        },

                        575:{
                            slidesPerView : 1
                        }
                    }
                }
            }
        }
    }
</script>
