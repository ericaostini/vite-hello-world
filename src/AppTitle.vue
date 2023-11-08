<template>
    <header>
        <h1>{{ titolo }}</h1>
    </header>
    <AppHero />
</template>

<script>
    import AppHero from './components/AppHero.vue'
    export default {
        name: 'AppTitle',
        components: {
            AppHero
        },
        data() {
            return {
                titolo: 'La mia prima app con Vite!'
            }
        },
    }
</script>

<style lang="css">
    h1{
        text-align: center;
        color: #009BDA;
    }
    header{
        padding: 20px;
        background-color: black;
    }
</style>
