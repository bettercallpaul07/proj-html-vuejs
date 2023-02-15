<script>

export default {
    name: "AppNews",
}

</script>

<template>

    <section>
        <div class="mediumContainer">
            <div class="txtContainer">
                <h5>Latest News</h5>
                <h2>Stay Updated With Our Latest News Articles</h2>
            </div>
            <div class="arrowList">
                <img src="../assets/img/svg/arrowleft.svg">
                <img class="green" src="../assets/img/svg/arrowright.svg">
            </div>
            <div class="cardContainer">
                <div class="card">
                    <img src="../assets/img/png/b1.png">
                    <div class="cardtxt">
                        <h4><b>Ninja Warrior Gaming</b></h4>
                        <div class="cardicon">
                            <span>
                                <img src="../assets/img/svg/youtube.svg">
                                By Admin
                            </span>
                            <span>|</span>
                            <span>
                                <img src="../assets/img/svg/calendar.svg">
                                Oct 25, 2022
                            </span>
                        </div>

                        <div class="btn-container">
                            <button>
                                Read More
                                <span>&#8594</span>
                            </button>
                        </div>
                    </div>


                </div>
                <div class="card">
                    <img src="../assets/img/png/b2.png">
                    <div class="cardtxt">
                        <h4><b>Gost Rider Retruns</b></h4>
                        <div class="cardicon">
                            <span>
                                <img src="../assets/img/svg/youtube.svg">
                                By Admin
                            </span>
                            <span>|</span>
                            <span>
                                <img src="../assets/img/svg/calendar.svg">
                                Oct 25, 2022
                            </span>
                        </div>

                        <div class="btn-container">
                            <button>
                                Read More
                                <span>&#8594</span>
                            </button>
                        </div>
                    </div>


                </div>
                <div class="card">
                    <img src="../assets/img/png/b3.png">
                    <div class="cardtxt">
                        <h4><b>Call of Deauty</b></h4>
                        <div class="cardicon">
                            <span>
                                <img src="../assets/img/svg/youtube.svg">
                                By Admin
                            </span>
                            <span>|</span>
                            <span>
                                <img src="../assets/img/svg/calendar.svg">
                                Oct 25, 2022
                            </span>
                        </div>

                        <div class="btn-container">
                            <button>
                                Read More
                                <span>&#8594</span>
                            </button>
                        </div>
                    </div>


                </div>
                <div class="card">
                    <img src="../assets/img/png/b4.png">
                    <div class="cardtxt">
                        <h4><b>Mortal Kombat X</b></h4>
                        <div class="cardicon">
                            <span>
                                <img src="../assets/img/svg/youtube.svg">
                                By Admin
                            </span>
                            <span>|</span>
                            <span>
                                <img src="../assets/img/svg/calendar.svg">
                                Oct 25, 2022
                            </span>
                        </div>

                        <div class="btn-container">
                            <button>
                                Read More
                                <span>&#8594</span>
                            </button>
                        </div>
                    </div>


                </div>
            </div>




        </div>

    </section>




</template>

<style lang="scss" scoped>
section {
    background-color: $darkblue-bg;
    height: 800px;

    .txtContainer {
        padding-bottom: 0.5rem;
        width: 60%;

        h5 {
            padding-bottom: 0.5rem;
        }

        h2 {
            font-size: 2.5rem;
        }
    }

    .cardContainer {
        display: flex;
        align-items: center;


        .card {
            width: 25%;
            margin-right: 1rem;


            img {
                width: 100%;
            }

            .cardtxt {
                width: 100%;
                height: 170px;
                background-color: $blue-bg;
                border-bottom-left-radius: 0.5rem;
                border-bottom-right-radius: 0.5rem;
                display: flex;
                flex-direction: column;
                align-items: center;

                h4 {
                    padding-top: 1rem;
                    color: white;
                }

                .cardicon {
                    display: flex;
                    color: $txt-primary;

                    span {
                        padding-top: 1rem;
                        padding-bottom: 1rem;
                        font-size: 0.7rem;
                        padding-left: 0.2rem;
                        padding-right: 0.2rem;
                        display: flex;
                        align-items: center;
                        justify-content: center;

                        &:nth-child(2) {
                            color: green;
                        }
                    }

                    span img {
                        background-color: $txt-secondary;
                        width: 1rem;
                        height: 1rem;
                        border-radius: 50%;
                        line-height: 1rem;
                        padding: 0.2rem;
                        margin-right: 0.2rem;
                    }
                }
            }
        }
    }
}
</style>