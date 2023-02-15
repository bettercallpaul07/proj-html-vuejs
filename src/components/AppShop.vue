<script>

export default {
    name: "AppShop",
}

</script>

<template>

    <section>
        <div class="mediumContainer">
            <div class="title-section">
                <h5>Gamer Shop</h5>
                <h2>Explore Our Shop</h2>
            </div>
            <div class="arrowList">
                <img src="../assets/img/svg/arrowleft.svg">
                <img class="green" src="../assets/img/svg/arrowright.svg">
            </div>

        </div>



    </section>




</template>

<style lang="scss" scoped>
section {
    background-image: url(../assets/img/png/shop-bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    filter: opacity(60%);
    z-index: 3;
    height: 400px;

    .arrowList {
        z-index: 2;

    }
}
</style>