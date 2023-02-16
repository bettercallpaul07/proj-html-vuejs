<script>


export default {
    name: "Navbar",
    data() {
        return {
            links: [
                {
                    label: 'Home',
                    url: '#',
                    active: false
                },
                {
                    label: 'Pages',
                    url: '#',
                    active: true
                },
                {
                    label: 'Tournament',
                    url: '#',
                    active: false
                },
                {
                    label: 'Shop',
                    url: '#',
                    active: false
                },
                {
                    label: 'Blog',
                    url: '#',
                    active: false
                },
                {
                    label: 'Contact',
                    url: '#',
                    active: false
                },
            ]
        };
    },
}


</script>

<template>
    <div class="navbar">
        <!-- logo -->
        <div class="logo">
            <img src="../assets/img/png/menulogo.png" alt="logo">
        </div>
        <!-- menù di navigazione -->
        <div class="menu">
            <ul>
                <li v-for="element in links" :class="{ active: element.active == true }">
                    <a :href="element.url">
                        {{ element.label }}
                    </a>
                </li>
            </ul>
        </div>
        <!-- icone navbar -->
        <div class="ic-li">
            <img class=icon src="../assets/img/svg/search.svg" alt="search">
            <img class=icon src="../assets/img/svg/shoppingbag.svg" alt="shop">
        </div>
</div>
</template>


<style lang="scss" scoped>
.navbar {
    max-width: 80vw;
    margin: 0 auto;
    padding: 0.5rem;
    height: 100px;
    display: flex;
    align-items: center;
    justify-content: space-between;

    .logo {

        img {
            max-width: 150px;
            max-height: 150px;
        }
    }

    .menu {
        ul li {
            list-style: none;
            display: inline-block;
        }

        a {
            padding: 0rem 1rem;
            text-transform: uppercase;
            text-decoration: none;
            color: $txt-primary;

            &:hover {
                color: lightgreen;

            }
        }
    }

    .ic-li {
        display: flex;

        img {
            @include icon;
            margin: 0 0.3rem;
            background-color: white;
            display: inline;
        }
    }
}
</style>