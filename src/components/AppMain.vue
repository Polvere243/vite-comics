<script>
export default {
    data: () => ({
        name: "AppMain",
        props: {
            thumb: String,
            series: String,

        }
    })
}
</script>
    


<template>
    <section id="comics-list">
        <div class="container">
            <button class="series">CURRENT SERIES</button>
            <div class="row">
                <div class="card" v-for="(comic, i) in comics" :key="i">
                    <figure>
                        <img :src="comic.thumb" :alt="comic.series" />
                        <figcaption>
                            <h4>{{ comic.series }}</h4>
                        </figcaption>
                    </figure>
                </div>
            </div>
            <div class="btn-box">
                <button class="more">
                    <h3>LOAD MORE</h3>
                </button>

            </div>

        </div>
    </section>
</template>

<style lang="scss" scoped>
/* sfondo della sezione */

#comics-list {
    background-color: black;
}

/* contenitore */
.container {
    max-width: 1080px;
    margin: 0 auto;
}

/* bottone */

.series {
    background-color: dodgerblue;
    padding: 5px 10px;
    color: white;
    position: relative;
    left: 0;
    top: 0;
    transform: translateY(-50%);
    border: none;
}

/* riga */

.row {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    width: 100%;

    /* card */
    .card {
        padding: 0 10px;
        margin-bottom: 20px;
        max-width: calc(100% / 6);
        display: flex;
        flex-direction: column;
        align-items: center;

        img {
            max-width: 100%;
        }
    }
}




figure {
    text-align: center;

    figcaption {
        width: 100%;
        text-align: left;
        margin-top: 10px;

        h4 {
            color: white;
            font-size: 14px;
        }
    }
}



/* pulsante */
.btn-box {
    margin-top: 20px;
    text-align: center;

    .more {
        padding: 10px 50px;
        background-color: dodgerblue;
        border: none;
        color: white;
        margin-bottom: 20px;
        font-weight: 100;
        font-size: 12px;
    }
}
</style>
