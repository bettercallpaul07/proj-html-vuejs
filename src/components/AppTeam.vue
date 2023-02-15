<script>

export default {
    name: "AppTeam",
}

</script>

<template>

    <section>
        <div class="mediumContainer">
            <div class="title-section">
                <h5>Team Members</h5>
                <h2>Our Experts Team Members</h2>
            </div>
            <div class="arrowList">
                <img src="../assets/img/svg/arrowleft.svg">
                <img class="green" src="../assets/img/svg/arrowright.svg">
            </div>

            <div class="cardSection">
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/team1.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Cristiano Messi</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>
                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/team2.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Sergio Neymaer</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>

                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/team3.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Antonella Roccuzzo</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>

                    </div>

                </div>
                <div class="cardTypeTwo">
                    <div class="imgContainer">
                        <img src="../assets/img/png/team4.png">

                    </div>
                    <div class="txtContainer">
                        <div>
                            <h3>Lionel Ramos</h3>
                            <p>Lorem, ipsum dolor.</p>
                        </div>

                    </div>

                </div>

            </div>

        </div>



    </section>




</template>

<style lang="scss" scoped>
section {
    background-color: $blue-bg;
    height: 600px;

    .cardSection {
        display: flex;
        align-items: center;
        justify-content: center;

        .cardTypeTwo {
            margin: 0 1rem;
            text-align: center;

            .txtContainer {
                background-color: $card;

                h3 {
                    font-weight: bold;
                    padding-top: 0.5rem;
                    padding-bottom: 0.5rem;
                    color: $txt-primary;
                }

                p {
                    padding-bottom: 0.5rem;
                }
            }
        }
    }
}
</style>