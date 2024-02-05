<script>
export default {
    name: "FooterBar"
}
</script>

<template>
    <section id="shop-sections">
        <ul class="links-pic">
            <li>
                <a href="#">
                    <img src="../assets/assets-vue-dc-comics-1/img/buy-comics-digital-comics.png" alt="kindle">
                    <h4>DIGITAL COMICS</h4>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/assets-vue-dc-comics-1/img/buy-comics-merchandise.png" alt="maglietta">
                    <h4>DC MERCHANDISE</h4>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/assets-vue-dc-comics-1/img/buy-comics-shop-locator.png" alt="tessere">
                    <h4>SUBSCRIPTION</h4>
                </a>
            </li>
            <li>
                <a href="#">
                    <img src="../assets/assets-vue-dc-comics-1/img/buy-comics-subscriptions.png"
                        alt="icona della posizione">
                    <h4>COMIC SHOP LOCATOR</h4>
                </a>
            </li>
            <li>
                <a href="#">
                    <img class="visa" src="../assets/assets-vue-dc-comics-1/img/buy-dc-power-visa.svg" alt="carta visa">
                    <h4>DC POWER VISA</h4>
                </a>
            </li>
        </ul>
    </section>
</template>

<style lang="scss" scoped>
/* link alle sezioni del negozio */
#shop-sections {
    height: 100px;
    background-color: dodgerblue;
}

.links-pic {
    max-width: 1080px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 100%;
    padding: 0 20px;
}

.links-pic img {
    max-width: 100%;
    height: 35px;
}

.links-pic li a {
    display: flex;
    gap: 10px;
    align-items: center;
    text-decoration: none;
    color: white;
    font-size: 14px;
}
</style>