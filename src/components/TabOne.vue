<template>
    <div class="ht-tab-wrap">
        <b-tabs class="ht-tab-menu wow move-up">
            <!-- <b-tab title="Destacados" active>
                <TabContentOne />  
            </b-tab> -->
            <b-tab title="Nuestro apoyo amistoso">
                <TabContentThree /> 
            </b-tab>
            <b-tab title="Nuestra Misión">
                <TabContentTwo /> 
            </b-tab>
        </b-tabs>
    </div>
</template>

<script>
    import TabContentOne from '../components/TabContentOne'
    import TabContentTwo from '../components/TabContentTwo'
    import TabContentThree from '../components/TabContentThree'

    export default {
        name: 'TabOne',
        components: {
            TabContentOne,
            TabContentTwo,
            TabContentThree
        }
    };
</script>