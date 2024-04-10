<template>
        <h1>{{ title }}</h1>
        <Jumbo2Component />
</template>

<script>
import Jumbo2Component from './ApptitleComponents/Jumbo2Component.vue';

    export default {
        name: 'TitleComponent',
        components:{
            Jumbo2Component,
        },
        data(){
            return{
                title: 'La mia prima app con Vite!',
            }
        }
    }
</script>

<style scoped>

    h1{
        color: rgb(255, 208, 0);
        text-align: center;
        /* background-color: brown; */
    }
</style>