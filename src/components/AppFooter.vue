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
            <div>
                <h5>DC COMICS</h5>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
            <div>
                <h5>SHOP</h5>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div>
                <h5>DC</h5>
                <ul>
                    <li>Terms of Use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC Certificates</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            <div>
                <h5>SITES</h5>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>
        </section>
        <section id="button-links">
            <div>
                <button class="sign-up">SIGN-UP NOW!</button>
            </div>
            <div>
                <h5>FOLLOW US</h5>
                <ul>
                    <li>
                        <a href="#">
                            <img src="../assets/assets-vue-dc-comics-1/img/footer-facebook.png" alt="logo di facebook" />
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
                            <img src="../assets/assets-vue-dc-comics-1/img/footer-pinterest.png" alt="logo di pinterest" />
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <img src="../assets/assets-vue-dc-comics-1/img/footer-periscope.png" alt="logo di periscope" />
                        </a>
                    </li>
                </ul>
            </div>
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
    height: 500px;
    background-image: url(../assets/assets-vue-dc-comics-1/img/footer-bg.jpg);
}
</style>