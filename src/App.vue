<template>
    <AppTitle />
    <JumboComponent />
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import JumboComponent from './components/JumboComponent.vue';

    export default {
        name: 'App',
        components: {
            AppTitle,
            JumboComponent,
        },
        data(){
            return{

            }
        }
    }
</script>

<style scoped>

</style>