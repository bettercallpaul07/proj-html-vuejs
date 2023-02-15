<script>

export default {
    name: "AppTrending",
}

</script>

<template>

    <section>
        <div class="mediumContainer">

            <div class="title-section">
                <h5>Trending Games</h5>
                <h2>Choose Who Is The Best in The World</h2>
            </div>
            <div class="arrowList">
                <img src="../assets/img/svg/arrowleft.svg">
                <img class="green" src="../assets/img/svg/arrowright.svg">
            </div>
            <div class="cardSection">
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/protfolio1.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Assassin's Creed</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>
                        <img src="../assets/img/svg/play.svg">

                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/protfolio2.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Call of Deauuty</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>
                        <img src="../assets/img/svg/play.svg">

                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/protfolio3.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Tomb Raider</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>
                        <img src="../assets/img/svg/play.svg">

                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/protfolio4.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Mortal Combat X</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>
                        <img src="../assets/img/svg/play.svg">

                    </div>

                </div>

            </div>

        </div>


    </section>




</template>

<style lang="scss" scoped>
section {
    background-image: url(../assets/img/png/Vector.png);
    height: 600px;



    .arrowList {
        padding-top: 1rem;
        padding-bottom: 1rem;
    }

    .cardSection {
        display: flex;
        align-items: center;
        justify-content: center;

        .cardTypeTwo {
            margin: 0 1rem;

            .txtContainer {
                display: flex;
                align-items: center;
                justify-content: space-between;

                h3 {
                    font-weight: bold;
                    color: $txt-primary;
                }

                img {
                    @include icon;
                    background-color: $txt-secondary;
                    margin-right: 0.3rem;
                }
            }
        }
    }
}
</style>

