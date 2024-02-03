<script>
import AppHeader from 'components/AppHeader.vue'
export default {
    components: {
        AppHeader
    }
}

</script>

<template>
    <div class="container"></div>
    <AppHeader></AppHeader>
</template>

<style>
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

/* contenitore */

.container {
    max-width: 1080px;
    margin: 0 auto;
}
</style>
