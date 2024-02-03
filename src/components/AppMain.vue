<script>
export default {

}
</script>

<template>
    <div class="container">
        <button class="series">CURRENT SERIES</button>
        <div class="row">
            <div class="card">
                <figure>
                    <img src="" />
                </figure>
                <figcaption></figcaption>
            </div>
        </div>
    </div>
</template>

<style>
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
    align-content: flex-start;
}

/* card */

.card {
    padding: 0 10px;
    margin-bottom: 20px;
}
</style>