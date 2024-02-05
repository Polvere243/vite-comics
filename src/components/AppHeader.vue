<script>
export default {
    name: "AppHeader",

    data: () => ({
        links: [
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
            const url = new URL("", import.meta.URL)
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
                <li v-for="(link, i) in links" :key="i">
                    <a :href="link.url">{{ link.text }}</a>
                </li>
            </ul>
        </nav>
    </header>
    <div class="jumbotron"></div>
</template>

<style lang="scss" scoped>
/* generico */
header {
    height: 80px;
    max-width: 1080px;
    margin: 0 auto;
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

/* contenitori dei link */

nav ul li {
    height: 100%;
    line-height: 80px;
    vertical-align: middle;

    /* link */
    a {
        text-decoration: none;
        color: black;
        text-transform: uppercase;
        font-size: 10px;
        font-weight: 500;
    }

    &.active,
    &:hover {
        border-bottom: 4px solid dodgerblue;
    }
}




/* jumbotron */

.jumbotron {
    height: 500px;
    background-image: url(../assets/assets-vue-dc-comics-1/img/jumbotron.jpg);
    background-position: center, top;
    background-size: cover;
    background-repeat: no-repeat;
}
</style>
