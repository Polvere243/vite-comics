<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/Appfooter.vue'

export default {
    components: {
        AppHeader,
        AppMain,
        AppFooter
    }
}
</script>

<template>
    <AppHeader></AppHeader>
    <AppMain></AppMain>
    <AppFooter></AppFooter>
</template>

<style lang="scss">
/* css reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Open Sans;
    font-family: Open Sans Condensed;
}

/* generici */
ul {
    list-style-type: none;
}

img {
    display: block;
}

a {
    text-decoration: none;
}
</style>
