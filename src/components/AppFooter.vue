<script>

export default {
    name: "AppFooter",
}

</script>

<template>

    <footer>
        <div class="newsletter">
            <div class="nsText">
                <h2>Our Newsletter</h2>


            </div>
            <div class="box">
                <div class="mail">
                    <img src="../assets/img/svg/message.svg">
                    <span>Enter your Email</span>
                </div>

                <div class="btn-circle">
                    <button>
                        Subscribe
                    </button>
                </div>
            </div>


        </div>




        <div class="mediumContainer">
            <div class="upper dflex">
                <div class="logo">
                    <img src="../assets/img/png/menulogo.png" alt="logo">
                </div>
                <div>
                    <ul>
                        <li>Home</li>
                        <li>Pages</li>
                        <li>Tournament</li>
                        <li>Shop</li>
                        <li>Blog</li>
                        <li>Contact</li>
                    </ul>
                </div>
            </div>

            <hr>
            <div class="lower dflex">
                <p>
                    Copyright Boolean | Designed by BetterCallPaul
                </p>
                <div class="horizontal-list">
                    <img src="../assets/img/svg/facebook.svg" alt="facebook">
                    <img src="../assets/img/svg/twitter.svg" alt="twitter">
                    <img src="../assets/img/svg/linkedin.svg" alt="linkedin">
                    <img src="../assets/img/svg/instagram.svg" alt="instagram">

                </div>
            </div>
        </div>
    </footer>




</template>

<style lang="scss" scoped>
footer {

    .newsletter {
        position: absolute;
        width: 800px;
        margin: 0 auto;
        height: 125px;
        position: absolute;
        top: -75px;
        left: 200px;
        background-color: $blue-bg;
        display: flex;
        align-items: center;
        justify-content: space-between;
        border-radius: 0.5rem;

        .nsText {
            display: flex;
            justify-content: space-between;
            align-items: center;

            h2 {
                color: white;
                padding-left: 2rem;
            }

        }

        .box {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background-color: $darkblue-bg;
            margin: 0 2rem;
            border-radius: 2rem;
            width: 400px;
            height: 60px;

            .btn-circle {
                width: 10rem;
                height: 1rem;
                display: flex;
                align-items: center;
                justify-content: center;

                button {
                    padding: 10px 20px;
                    background-color: $txt-secondary;
                    border-radius: 2rem;
                    font-weight: bold;
                }
            }

            .mail {

                display: flex;
                align-items: center;
                color: gray;
                font-size: 0.7rem;

                img {
                    margin-left: 1rem;
                    width: 2rem;
                    height: 2rem;
                    line-height: 2rem;
                    padding: 0.5rem;
                    filter: invert(1);

                }

            }


        }

    }

    position: relative;
    background-image: url(../assets/img/png/banner1.png);
    background-repeat: no-repeat;
    background-size: cover;
    max-height: 300px;
    padding-top: 5rem;
    padding-bottom: 1rem;


    .mediumContainer {

        .upper {
            align-items: center;
            justify-content: space-between;
            margin-bottom: 2rem;

            .logo {
                img {
                    max-width: 200px;
                    max-height: 200px;
                }
            }

            ul li {
                list-style: none;
                display: inline-block;
                color: $txt-primary;
                padding-right: 0.5rem;
                text-transform: uppercase;
                font-weight: bold;
            }

        }

        .lower {
            margin-top: 0.3rem;
            align-items: center;
            justify-content: space-between;
            color: $txt-primary;
            font-size: 0.7rem;

            .horizontal-list {

                img {
                    background-color: $blue-bg;
                    @include icon;
                    margin: 0 auto;
                    margin-right: 0.3rem;
                }
            }

        }

    }
}
</style>