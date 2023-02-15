<script>

export default {
    name: "AppUpcomingTrending",
}

</script>

<template>

    <section>
        <div class="title-section">
            <h5>TrendingBattle</h5>
            <h2>AppUpcoming Match</h2>
            <ul>
                <li>All</li>
                <li>Pubg</li>
                <li>COD</li>
                <li>AC</li>
                <li>MCX</li>
            </ul>
        </div>
        <div>
            <div class="horizontalCard">
                <div class="battleCard">
                    <div class="battleContainer">
                        <img src="../assets/img/png/t3.png" alt="">
                        <div class="txtContainer">
                            <h5>Italy</h5>
                            <p>Ninga Gaming</p>
                        </div>
                    </div>
                    <div class="versus">
                        <p>VS</p>
                    </div>
                    <div class="battleContainer">
                        <img src="../assets/img/png/t4.png" alt="">
                        <div class="txtContainer">
                            <h5>India</h5>
                            <p>Witch Gaming</p>
                        </div>
                    </div>

                    <div class="battle-txt">
                        <h2>PUGB Battleground</h2>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Provident officia reprehenderit
                            beatae ipsa ipsam accusamus quam vel tenetur consectetur iusto.</p>
                    </div>

                    <div class="hour">
                        <h4>10:45</h4>
                        <h6>1st November, 2022</h6>

                        <div class="hourIcon">
                            <img src="../assets/img/svg/youtube.svg">
                            <img src="../assets/img/svg/message.svg">
                        </div>

                    </div>

                </div>

            </div>
            <div class="horizontalCard">
                <div class="battleCard">
                    <div class="battleContainer">
                        <img src="../assets/img/png/t1.png" alt="">
                        <div class="txtContainer">
                            <h5>Italy</h5>
                            <p>Ninga Gaming</p>
                        </div>
                    </div>
                    <div class="versus">
                        <p>VS</p>
                    </div>
                    <div class="battleContainer">
                        <img src="../assets/img/png/t2.png" alt="">
                        <div class="txtContainer">
                            <h5>India</h5>
                            <p>Witch Gaming</p>
                        </div>
                    </div>

                    <div class="battle-txt">
                        <h2>PUGB Battleground</h2>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Provident officia reprehenderit
                            beatae ipsa ipsam accusamus quam vel tenetur consectetur iusto.</p>
                    </div>

                    <div class="hour">
                        <h4>10:45</h4>
                        <h6>1st November, 2022</h6>

                        <div class="hourIcon">
                            <img src="../assets/img/svg/youtube.svg">
                            <img src="../assets/img/svg/message.svg">
                        </div>

                    </div>

                </div>

            </div>
            <div class="horizontalCard">
                <div class="battleCard">
                    <div class="battleContainer">
                        <img src="../assets/img/png/t5.png" alt="">
                        <div class="txtContainer">
                            <h5>Italy</h5>
                            <p>Ninga Gaming</p>
                        </div>
                    </div>
                    <div class="versus">
                        <p>VS</p>
                    </div>
                    <div class="battleContainer">
                        <img src="../assets/img/png/t6.png" alt="">
                        <div class="txtContainer">
                            <h5>India</h5>
                            <p>Witch Gaming</p>
                        </div>
                    </div>

                    <div class="battle-txt">
                        <h2>PUGB Battleground</h2>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Provident officia reprehenderit
                            beatae ipsa ipsam accusamus quam vel tenetur consectetur iusto.</p>
                    </div>

                    <div class="hour">
                        <h4>10:45</h4>
                        <h6>1st November, 2022</h6>

                        <div class="hourIcon">
                            <img src="../assets/img/svg/youtube.svg">
                            <img src="../assets/img/svg/message.svg">
                        </div>

                    </div>

                </div>

            </div>
            <div class="horizontalCard">
                <div class="battleCard">
                    <div class="battleContainer">
                        <img src="../assets/img/png/t7.png" alt="">
                        <div class="txtContainer">
                            <h5>Italy</h5>
                            <p>Ninga Gaming</p>
                        </div>
                    </div>
                    <div class="versus">
                        <p>VS</p>
                    </div>
                    <div class="battleContainer">
                        <img src="../assets/img/png/t8.png" alt="">
                        <div class="txtContainer">
                            <h5>India</h5>
                            <p>Witch Gaming</p>
                        </div>
                    </div>

                    <div class="battle-txt">
                        <h2>PUGB Battleground</h2>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Provident officia reprehenderit
                            beatae ipsa ipsam accusamus quam vel tenetur consectetur iusto.</p>
                    </div>

                    <div class="hour">
                        <h4>10:45</h4>
                        <h6>1st November, 2022</h6>

                        <div class="hourIcon">
                            <img src="../assets/img/svg/youtube.svg">
                            <img src="../assets/img/svg/message.svg">
                        </div>

                    </div>

                </div>

            </div>

        </div>

    </section>




</template>

<style lang="scss" scoped>
section {
    @include container;
    height: 1000px;
    display: flex;
    flex-direction: column;
    align-items: center;

    .title-section {
        text-align: center;

        h5 {
            margin-top: 3rem;
            margin-bottom: 1rem;
        }

        ul {
            margin-top: 2rem;
            margin-bottom: 1rem;

            li {
                list-style: none;
                display: inline-block;
                padding: 0.5rem;
                color: white;
            }
        }

    }
}
</style>