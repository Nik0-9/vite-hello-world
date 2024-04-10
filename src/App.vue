<template>
    <header :class="{ 'invert': isInverted }"npm run dropdown-divider >
        <TitleComponent />
    </header>
    <button @click="toggleInvertClass">Applica filtro invert</button>
</template>

<script>
import TitleComponent from './components/TitleComponent.vue';

export default {
    name: 'App',
    components: {
        TitleComponent
    },
    data() {
        return {
            isInverted: false
        }
    },
    methods: {
        toggleInvertClass() {
            this.isInverted = !this.isInverted;
        }
    }
}
</script>

<style scoped>
.invert {
    filter: invert(1);
    transition: 5s;
}

button{
    padding: 10px;
}

header {
    background-color: brown;
    box-sizing: border-box;
    margin-bottom: 20px ;
    padding: 0;
}
</style>