<script>
export default {
    name: "AppFooter"
}
</script>

<template>
    <footer>
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
        <section id="site-links">
            <div class="lists-row">
                <div>
                    <h5>DC COMICS</h5>
                    <ul>
                        <li>
                            <a href="#">
                                Characters
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Comics
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Movies
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                TV
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Games
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Videos
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                News
                            </a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h5>SHOP</h5>
                    <ul>
                        <li>
                            <a href="#">
                                Shop DC
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Shop DC Collectibles
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <h5>DC</h5>
                    <ul>
                        <li>
                            <a href="#">
                                Terms of Use
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Privacy policy (New)
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Ad Choices
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Advertising
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Jobs
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Subscriptions
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Talent Workshops
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                CPSC Certificates
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Ratings
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Shop Help
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                Contact Us
                            </a>
                        </li>
                    </ul>
                </div>
                <div>
                    <h5>SITES</h5>
                    <ul>
                        <li>
                            <a href="#">
                                DC
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                MAD Magazine
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Kids
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Universe
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                DC Power Visa
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="button-links">
            <nav class="lower-footer">
                <div>
                    <button class="sign-up">SIGN-UP NOW!</button>
                </div>
                <div class="f-links">
                    <h5>FOLLOW US</h5>
                    <ul class="links-list">
                        <li>
                            <a href="#">
                                <img src="../assets/assets-vue-dc-comics-1/img/footer-facebook.png"
                                    alt="logo di facebook" />
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/assets-vue-dc-comics-1/img/footer-twitter.png" alt="logo di twitter" />
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/assets-vue-dc-comics-1/img/footer-youtube.png" alt="logo di youtube" />
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/assets-vue-dc-comics-1/img/footer-pinterest.png"
                                    alt="logo di pinterest" />
                            </a>
                        </li>
                        <li>
                            <a href="#">
                                <img src="../assets/assets-vue-dc-comics-1/img/footer-periscope.png"
                                    alt="logo di periscope" />
                            </a>
                        </li>
                    </ul>
                </div>
            </nav>


        </section>
    </footer>
</template>

<style scoped>
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


/* sfondo della sezione */

#site-links {
    background-image: url(../assets/assets-vue-dc-comics-1/img/dc-logo-bg.png), url(../assets/assets-vue-dc-comics-1/img/footer-bg.jpg);
    background-position: right center, center;
    background-repeat: no-repeat;
}

/* contenitore link */
.lists-row {
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    max-width: 500px;
    margin: 0 0 0 130px;
    height: 300px;
    padding: 20px 0 0 0;
}

footer h5 {
    color: white;
    font-weight: 800;
}

.lists-row a {
    color: rgb(135, 126, 126);
    font-size: 12px;
}

.lists-row li {
    flex-basis: 30px;
}

.lists-row div {
    margin-bottom: 10px;
}

/* ultima sezione */

#button-links {
    background-color: rgb(61, 60, 60);
    padding: 20px 0;
}

/* contenitore del footer in basso */
.lower-footer {
    max-width: 1080px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    height: 100%;
    align-items: center;
}

/* pulsante */

.sign-up {
    padding: 5px 10px;
    background-color: transparent;
    border: 1px solid dodgerblue;
    color: white;
    font-weight: 700;
}


/* lato dei link */
.f-links {
    display: flex;
    align-items: center;
    gap: 20px;
}

.links-list {
    display: flex;
    gap: 20px
}
</style>