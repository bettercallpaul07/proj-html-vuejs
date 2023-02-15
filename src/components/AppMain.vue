<script>

import AppFeature from "./AppFeature.vue";
import AppStreaming from "./AppStreaming.vue";
import AppUpcomingTrending from "./AppUpcomingTrending.vue";
import AppTrending from "./AppTrending.vue";
import AppUpcoming from "./AppUpcoming.vue";
import AppTeam from "./AppTeam.vue";
import AppTestimonial from "./AppTestimonial.vue";
import AppShop from "./AppShop.vue";
import AppNews from "./AppNews.vue";



export default {
    name: "AppMain",
    data() { return {
    }
    },
        components: {
        AppFeature,
        AppStreaming,
        AppUpcomingTrending,
        AppTrending,
        AppUpcoming,
        AppTeam,
        AppTestimonial,
        AppShop,
        AppNews
    },

    };


</script>

<template>
    <main>

        <AppFeature />
        <AppStreaming />
        <AppUpcomingTrending />
        <AppTrending />
        <AppUpcoming />
        <AppTeam />
        <AppTestimonial />
        <AppShop />
        <AppNews />

    </main>





</template>

<style lang="scss" scoped>
main {
    background-color: $blue-bg;

}
</style>