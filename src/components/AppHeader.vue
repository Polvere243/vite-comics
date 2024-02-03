<script>
export default {
    name: "AppHeader",

    data: () => ({
        li_links: [
            {
                text: 'Characters',
                url: '#',
                current: false,
            },
            {
                text: 'Comics',
                url: '#',
                current: true,
            },
            {
                text: 'Movies',
                url: '#',
                current: false,
            },
            {
                text: 'TV',
                url: '#',
                current: false,
            },
            {
                text: 'Games',
                url: '#',
                current: false,
            },
            {
                text: 'Collectibles',
                url: '#',
                current: false,
            },
            {
                text: 'Videos',
                url: '#',
                current: false,
            },
            {
                text: 'Fans',
                url: '#',
                current: false,
            },
            {
                text: 'News',
                url: '#',
                current: false,
            },
            {
                text: 'Shop',
                url: '#',
                current: false,
            },
        ]

    }),

    methods: {
        createPath(img) {
            const url = new URL("@/assets/vue-dc-comics-1/", import.meta.URL)
            return path.src;
        }
    }
}
</script>

<template>
    <header>
        <figure>
            <img src="../assets/assets-vue-dc-comics-1/img/dc-logo.png" alt="logo DC Comics" />
        </figure>
        <nav>
            <ul>
                <li>CHARACTERS</li>
                <li class="active">COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </header>
</template>

<style scoped>
/* generico */
header {
    max-width: 1080px;
    margin: 0 auto;
    height: 80px;
    display: flex;
    justify-content: space-between;
}

figure {
    display: flex;
    align-items: center;
}

nav ul {
    display: flex;
    align-items: center;
    gap: 20px;
    height: 100%;
}

/* immagine fluida */

img {
    max-width: 60px;
}

nav ul li {
    height: 100%;
    font-size: 12px;
    line-height: 80px;
    vertical-align: middle;
}

.active {
    border-bottom: 2px solid dodgerblue;
}
</style>
