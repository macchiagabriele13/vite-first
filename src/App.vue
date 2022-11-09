<script>

// #1 importo qui eventuali componenti

import AppTitle from "../src/components/AppTitle.vue";


// #2 definisco una proprietá components per registrare i componenti importati al punto 1
export default {

    components: {
        AppTitle
    }

}

</script>

<template>

    <AppTitle />

</template>

<style>

</style>
