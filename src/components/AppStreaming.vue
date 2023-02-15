<script>

export default {
    name: "AppStreaming",
}

</script>

<template>

    <section>
        <div class="left">
            <div class="box">
                <img class="cover" src="../assets/img/png/v-1.png" alt="v1">
                <div class="cntr-btn">
                    <img src="../assets/img/svg/play.svg" alt="play">
                    <p>Call Of Deauty</p>
                </div>
            </div>

        </div>


        <div class="right">
            <div class="littleContainer">
                <h5>Live Streaming</h5>
                <h2>Checkout Our Live Streaming</h2>

                <div class="arrowList">
                    <img src="../assets/img/svg/arrowleft.svg">
                    <img class="green" src="../assets/img/svg/arrowright.svg">
                </div>

                <div class="dflex">
                    <div>
                        <img src="../assets/img/png/v-small1.png">
                        <h6>Call of Deauty</h6>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Commodi, quae!</p>
                    </div>
                    <div>
                        <img src="../assets/img/png/v-small2.png">
                        <h6>Assaaain creed</h6>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Commodi, quae!</p>
                    </div>
                </div>
            </div>


        </div>

    </section>




</template>

<style lang="scss" scoped>
section {
    height: 500px;
    background-image: url(../assets/img/png/v-bg.png);
    filter: brightness(80%);
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;

    .left {
        display: flex;
        align-items: center;
        justify-content: flex-end;

        .box {
            @include imageStyleOne;
            position: relative;

            img {
                @include imageStyleOne;

            }

            .cntr-btn {

                position: absolute;
                top: 150px;
                right: 220px;
                text-align: center;

                img {
                    position: relative;
                    @include iconPlus;
                    color: white;
                    background-color: $txt-secondary;
                }

                p {
                    margin-top: 0.4rem;
                }

            }
        }
    }

    .right {
        display: flex;
        flex-direction: column;
        @include paddingTwo;

        h2 {
            font-size: 2.4rem;

        }

        p {
            font-size: 0.7rem;
        }

        img {
            @include imageStyleTwo;
        }

        * {
            padding-bottom: 0.8rem;
        }

        .arrowList {

            text-align: end;

            img {
                @include icon;
                background-color: $txt-primary;
                margin-left: 0.5rem;
            }

            .green {
                background-color: $txt-secondary;
            }
        }

    }
}
</style>