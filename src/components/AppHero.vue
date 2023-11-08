<template>
    <div>
        <h3>{{ hero }}</h3>
    </div>
</template>

<script>
    export default {
        name: 'AppHero',
        data() {
            return {
                hero: 'Benvenuto'
            }
        }
    }
</script>

<style lang="css">
    h3{
        background-image: url('/images/bg-img.jpg');
    }
</style>