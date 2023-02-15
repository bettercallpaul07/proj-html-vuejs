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
            <div class="shop">
                <div class="item">
                    <div class="imgbox">
                        <img src="../assets/img/png/s1.png">
                    </div>
                    <div>
                        <h4>Sony PlayStation 5</h4>
                    </div>

                </div>
                <div class="item">
                    <div class="imgbox">
                        <img src="../assets/img/png/s2.png">
                    </div>
                    <div>
                        <h4>Asus Rog</h4>
                    </div>

                </div>
                <div class="item">
                    <div class="imgbox">
                        <img src="../assets/img/png/s3.png">
                    </div>
                    <div>
                        <h4>Vr Visore Facebook</h4>
                    </div>

                </div>
                <div class="item">
                    <div class="imgbox">
                        <img src="../assets/img/png/s4.png">
                    </div>
                    <div>
                        <h4>Beats Studio 3 Cuffie</h4>
                    </div>

                </div>

            </div>

        </div>



    </section>




</template>

<style lang="scss" scoped>
section {
    background-image: url(../assets/img/png/shop-bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 500px;

    .shop {
        display: flex;
        align-items: center;

        .item {

            .imgbox {

                width: 175px;
                height: 150px;
                margin-right: 1rem;
                border-radius: 0.5rem;
                background-color: $darkblue-bg;
                display: flex;
                align-items: center;
                justify-content: center;

                img {
                    max-width: 150px;
                    max-height: 150px;
                    padding: 1rem;
                }



            }

            h4 {
                padding-top: 1rem;
                color: white;
            }

        }




    }


}
</style>