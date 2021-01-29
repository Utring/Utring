<template>
    <div class="start-ups-feature-wrap">
        <div class="modern-grid">
            <div v-for="iconbox in iconboxs" :key="iconbox.id" class="ht-box-icon style-02 wow move-up">
                <router-link :to="'branding'" class="link-secret">
                    <div class="icon-box-wrap">
                        <div class="icon react" :class="{'java':iconbox.java, 'macos':iconbox.macos, 'window':iconbox.window, 'android':iconbox.android, 'php':iconbox.php}">
                            <span :class="iconbox.icon" :data-icon="iconbox.data_icon"></span>
                        </div>
                        <div class="content">
                            <h6 class="heading">{{ iconbox.heading }}</h6>
                        </div>
                    </div>
                </router-link>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'StartUpFeature',
        data (){
            return {
                iconboxs: [
                    {
                        icon: 'iconify', 
                        heading: 'C',
                        data_icon: "mdi:language-c",
                    },
                    {
                        icon: 'iconify', 
                        heading: 'C++', 
                        data_icon: "gg-c-plus-plus",
                        window:true
                    },
                    {
                        icon: 'fab fa-java', 
                        heading: 'Java', 
                        macos:true
                    },
                    {
                        icon: 'fab fa-js', 
                        heading: 'Javascript', 
                        java:true
                    },
                    {
                        icon: 'fab fa-python', 
                        heading: 'Python', 
                        android:true
                    },
                    {
                        icon: 'fab fa-r-project', 
                        heading: 'R', 
                        php:true
                    },
                ]
            }
        }
    }
</script>
