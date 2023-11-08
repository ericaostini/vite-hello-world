<template>
    <header>
        <h1>{{ titolo }}</h1>
    </header>
</template>

<script>
    export default {
        nome: 'AppTitle',
        components: {

        },
        data() {
            return {
                titolo: 'La mia prima app con Vite!'
            }
        },
    }
</script>

<style lang="scss" scoped>

</style>
