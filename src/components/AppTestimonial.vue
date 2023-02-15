<script>

export default {
    name: "AppTestimonial",
}

</script>

<template>

    <section>

        <div class="mediumContainer">
            <div class="title-section">
                <h5>Testimonial</h5>
                <h2>What Our Client Say</h2>
            </div>

            <div class="arrowList">
                <img src="../assets/img/svg/arrowleft.svg">
                <img class="green" src="../assets/img/svg/arrowright.svg">
            </div>

            <div class="clientImage">
                <img src="../assets/img/png/test1.png">
                <img src="../assets/img/png/test2.png">
                <img src="../assets/img/png/test3.png">
                <img src="../assets/img/png/test4.png">


            </div>


        </div>


    </section>




</template>

<style lang="scss" scoped>
section {

    background-image: url(../assets/img/png/test-grouptwo.png);
    background-size: cover;
    background-repeat: no-repeat;
    height: 500px;

    .clientImage {
        display: flex;

        img {
            max-width: 200px;
            margin-right: 1rem;
        }
    }
}
</style>