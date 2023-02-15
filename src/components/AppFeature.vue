<script>

export default {
    name: "AppFeature",
}

</script>

<template>

    <section class="container">
        <div class="left">
            <h5>
                Our Extreme Feature
            </h5>
            <h2>
                The Best Gaming Arena on The World!
            </h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem blanditiis dignissimos labore soluta ipsum, hic veritatis architecto obcaecati dolore assumenda voluptas, rem dolorum quae distinctio possimus autem facilis temporibus quos.</p>

        </div>
        <div class="right">

            <div class="cardcontainer">
                <div class="cardtypeone green">
                    <img src="../assets/img/png/feature1.png" alt="1">
                    <h3>Live Streaming</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, neque.</p>
                </div>
                <div class="cardtypeone">
                    <img src="../assets/img/png/feature2.png" alt="2">
                    <h3>Gaming News</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, neque.</p>
                </div>
                <div class="cardtypeone">
                    <img src="../assets/img/png/feature3.png" alt="3">
                    <h3>Great Tournament</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, neque.</p>
                </div>
                <div class="cardtypeone green">
                    <img src="../assets/img/png/feature4.png" alt="4">
                    <h3>Adward Ceremony</h3>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Et, neque.</p>
                </div>
            </div>


        </div>

    </section>




</template>

<style lang="scss" scoped>
.container {
    background-image: url(../assets/img/png/Vector.png);

    .left {
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 500px;

        h5 {
            color: $txt-secondary;
            padding-bottom: 0.6rem;
        }

        h2 {
            color: $txt-primary;
            padding-bottom: 0.6rem;
        }

        p {
            color: $txt-primary;
            font-size: 0.8rem;
            line-height: 1.2rem;
        }
    }

    .right {
        display: flex;
        align-items: center;
        justify-content: center;

        .cardcontainer {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            max-height: 800px;
            max-width: 500px;

            .cardtypeone {
                margin: 15px;
                background-color: $card;
                color: white;

                &.green {
                    background-color: $txt-secondary;
                    color: black;
                }
            }

        }

    }
}
</style>