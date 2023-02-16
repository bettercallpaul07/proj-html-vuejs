<script>

export default {
    name: "Navbar",
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
                <li>
                    <a href="#">Home</a>
                    <a href="#">Pages</a>
                    <a href="#">Tournament</a>
                    <a href="#">Shop</a>
                    <a href="#">Blog</a>
                    <a href="#">Contact</a>
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

            a {
                padding: 0rem 1rem;
                color: $txt-primary;
                text-transform: uppercase;
                text-decoration: none;
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