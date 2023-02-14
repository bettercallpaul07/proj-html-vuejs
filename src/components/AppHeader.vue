<script>

export default {
    name: "AppHeader",
}

</script>

<template>

    <header>
        <div class="main-header">
            <div class="navbar">
                <div class="logo">
                    <img src="../assets/img/png/menulogo.png" alt="logo">
                </div>

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

                <div class="ic-li">
                    <img class=icon src="../assets/img/svg/search.svg" alt="search">
                    <img class=icon src="../assets/img/svg/shoppingbag.svg" alt="shop">

                </div>
            </div>
            <div class="main-title">
                <div class="vertical-list">
                    <img src="../assets/img/svg/facebook.svg" alt="facebook">
                    <img src="../assets/img/svg/twitter.svg" alt="twitter">
                    <img src="../assets/img/svg/linkedin.svg" alt="linkedin">
                    <img src="../assets/img/svg/instagram.svg" alt="instagram">

                </div>
                <div class="title">
                    <h5>Welcome to Raxg</h5>
                    <h1>Are you ready for your next challenge?</h1>
                    <div class="btn-container">
                        <button>
                            Read More
                            <span>&#8594</span>
                        </button>
                        <img src="../assets/img/svg/play.svg" alt="play">
                    </div>

                </div>
            </div>


        </div>

        <div class="discover">
            <div class="list-header">
                <img src="../assets/img/png/1.png" alt="1">
                <img src="../assets/img/png/2.png" alt="2">
                <img src="../assets/img/png/3.png" alt="3">
                <img src="../assets/img/png/4.png" alt="4">
                <img src="../assets/img/png/5.png" alt="5">
                <img src="../assets/img/png/6.png" alt="6">
            </div>

            <div class="container">

                <div class="left">
                    <div>
                        <img src="../assets/img/png/exprince.jpg" alt="prince">
                        <img id="shadow" src="../assets/img/png/exprience-shape.png">
                        <img id="shape1" src="../assets/img/png/shape1.png" alt="">
                        <img id="shape2" src="../assets/img/png/shape2.png" alt="">
                        <img id="shape3" src="../assets/img/png/shape2.png" alt="">
                        <img id="shape4" src="../assets/img/png/shape2.png" alt="">


                    </div>

                </div>

                <div class="right">
                    <div class="info-box">
                        <h5>12 Year Experience</h5>
                        <h2>We Are The Best Gaming Company</h2>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nisi, a corporis ipsa velit
                            laboriosam
                            magni nesciunt voluptatum maxime reprehenderit eius in similique nihil sapiente non nemo ut
                            est
                            blanditiis veniam, eligendi ad nulla doloribus nam commodi? Qui laudantium sequi quae beatae
                            itaque quam consequuntur. Suscipit tenetur sequi iste blanditiis. Veritatis.</p>
                        <ul>
                            <li><span>&#x2713;</span>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
                            <li><span>&#x2713;</span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi.</li>
                            <li><span>&#x2713;</span>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
                            <li><span>&#x2713;</span>Lorem ipsum dolor sit amet consectetur adipisicing elit.</li>
                        </ul>
                        <div class="btn-container">
                            <button>
                                Discover More
                                <span>&#8594</span>
                            </button>
                            <img class="principal" src="../assets/img/svg/play.svg" alt="play">
                        </div>
                    </div>

                </div>
            </div>




        </div>

        <div>


        </div>
    </header>



</template>

<style lang="scss" scoped>
header {
    min-height: 100vh;

    .main-header {
        background-image: url("../assets/img/png/banner1.png");
        background-repeat: no-repeat;
        background-size: cover;
        min-height: 700px;
        width: 100%;

        .navbar {
            @include container;
            padding: 0.5rem;
            height: 100px;
            display: flex;
            align-items: center;
            justify-content: space-between;

            .logo {
                height: 80%;

                img {
                    max-width: 100%;
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
                img {
                    @include icon;
                    margin: 0 0.3rem;
                    background-color: white;
                    display: inline;
                }
            }
        }
    }

    .main-title {
        @include container;
        display: flex;
        align-items: center;
        justify-content: center;
        margin-top: 13rem;
        text-transform: uppercase;
        position: relative;

        .vertical-list {
            display: flex;
            flex-direction: column;
            height: 100px;
            width: 50px;
            position: absolute;
            left: 0;
            top: 0;

            img {
                background-color: white;
                @include icon;
                margin-top: 1rem;
                max-height: 100%;
            }
        }

        .title {
            h1 {
                width: 60%;
                margin: 0 auto;
                line-height: 5rem;
                text-align: center;
                color: $txt-primary;
                font-size: 4rem;
            }

            h5 {
                text-align: center;
                color: $txt-secondary;

            }

            .btn-container {
                margin: 0 auto;
            }
        }

    }

    .list-header {
        width: 50%;
        margin: 0 auto;
        height: 150px;
        position: absolute;
        top: -10%;
        left: 25%;
        background-color: $blue-bg;
        display: flex;
        align-items: center;
        justify-content: space-between;

        img {
            padding: 1.5rem 3rem;
            width: calc(100%/6);
            height: 100%;
        }
    }

    .discover {
        position: relative;
        min-height: 700px;
        margin: 0 auto;
        background-color: $darkblue-bg;
    }
}

.container {

    .left {
        position: relative;

        #shadow {
            position: absolute;
            top: 24%;
            left: 19%;
            width: 10%;
            height: 10%;
            z-index: 3;
        }

        #shape1 {
            position: absolute;
            top: 25%;
            left: 25%;
            width: 5%;
            height: 40%;
            z-index: 1;
        }

        #shape2 {
            position: absolute;
            top: 20%;
            left: 25%;
            width: 40%;
            height: 5%;
            z-index: 2;

        }

        #shape3 {
            position: absolute;
            top: 75%;
            left: 50%;
            width: 40%;
            height: 5%;

        }

        #shape4 {
            position: absolute;
            top: 40%;
            left: 90%;
            width: 5%;
            height: 40%;
            z-index: 2;

        }

        img {
            position: absolute;
            top: 25%;
            right: 10%;
            width: 60%;
            height: 50%;
        }
    }

    .right {
        position: relative;

        .info-box {
            position: absolute;
            top: 20%;
            left: 5%;
            min-height: 500px;

            
        h5 {
            color: $txt-secondary;
            padding-bottom: 1rem;
        }

        h2 {
            color: $txt-primary;
            padding-bottom: 2rem;
            font-size: 2.5rem;

        }

        p {
            color: $txt-primary;
            padding-bottom: 2rem;
            line-height: 1.5rem;
        }

        ul li {
            list-style: none;
            color: white;
            padding-bottom: 1rem;

            span {
                border: 1px solid $txt-secondary;
                border-radius: 50%;
                color: $txt-secondary;
                padding: 0.1rem;
                margin-right: 0.5rem;
            }

        }

        }

    }


}
</style>