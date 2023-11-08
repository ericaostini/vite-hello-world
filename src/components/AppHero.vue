<template>
    <main>
        <h3>{{ hero }}</h3>
    </main>
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
    main{
        background-image: url('/images/bg-img.jpg');
        background-size: contain;
        background-repeat: no-repeat;
        background-position: top center;
        position: relative;
    }
    h3{
        font-size: 100px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
    }
</style>