<template>
    <header>
        <h1>{{ titolo }}</h1>
    </header>
    <main>
        
    </main>
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
        margin-top: 10px;
    }
</style>
