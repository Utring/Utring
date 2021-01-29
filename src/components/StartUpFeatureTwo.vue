<template>
    <div class="row">
        <div v-for="item in items" :key="item.id" class="col-lg-4 col-md-6 wow move-up">
            <div class="service-grid">
                <div class="ht-service-box--two text-center style-03">
                    <router-link to="">
                        <div class="image mb-20">
                            <img :src="item.icon" class="img-fluid" alt="aeroland-startup-box-icon-01">
                        </div>
                        <div class="content">
                            <h6 class="heading">{{ item.heading }}</h6>
                            <div class="service_text">{{ item.text }}</div>
                        </div>
                    </router-link>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'StartUpFeatureTwo',
        data (){
            return {
                items: [
                    {
                       icon: require('../assets/img/icons/analysis.png'), 
                       heading: 'Ciencia de datos', 
                       text: 'Aplicación de Machine learning para detección de objetos y analitica de datos.'
                    },
                    {
                        icon: require('../assets/img/icons/computer.png'), 
                        heading: 'Desarrollo de apliaciones', 
                        text: 'Desarrollo de aplicaciones web, nativas, hibridas, PWA.'
                    },
                    {
                        icon: require('../assets/img/icons/api.png'), 
                        heading: 'Desarrollo de APIs y SDKs', 
                        text: 'Creación de librerias, interfaces de aplicaciones y kits de desarrollo para desarrolladores de software.'
                    },
                    {
                        icon: require('../assets/img/icons/video.png'), 
                        heading: 'Video Streaming', 
                        text: 'Soluciones en manipulación y transmisión de video en vivo usando tecnologias como WebRTC, RTSP, HLS, RTMP, OPENCV, FFmpeg, GStreamer, etc.'
                    },
                    {
                        icon: require('../assets/img/icons/cpu.png'), 
                        heading: 'Programación de microcontroladores', 
                        text: 'Desarrollo en sistemas embebidos usando Mbed, STM32, Arduino, ROS, RTOS, etc.'
                    },
                    {
                        icon: require('../assets/img/icons/pdf.png'), 
                        heading: 'Manejo y automatización de PDFs', 
                        text: 'Automatización en los procesos de extracción de información, firma y rellenado de archivos PDFs.'
                    },
                ]
            }
        }
    }
</script>
