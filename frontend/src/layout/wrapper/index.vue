<template>
    <div class="wrapper">
        <div class="header-wrapper">
            <TopCinema></TopCinema>
            <MenuCinema></MenuCinema>
        </div>
        <div class="page-wrapper">
            <div class="page-content">
                <router-view> </router-view>
            </div>
        </div>
        <BotCinema></BotCinema>
    </div>
</template>
<script>
import TopCinema from '../components/TopCinema.vue';
import MenuCinema from '../components/MenuCinema.vue';
import BotCinema from '../components/BotCinema.vue';
import "../../assets/js/bootstrap.bundle.min.js";
import "../../assets/js/jquery.min.js";
import "../../assets/plugins/simplebar/js/simplebar.min.js";
import "../../assets/plugins/metismenu/js/metisMenu.min.js";
import "../../assets/plugins/perfect-scrollbar/js/perfect-scrollbar.js";
import "../../assets/js/index.js";
import "../../assets/js/app.js";
import "../../assets/js/pace.min.js";
export default {
    name: "#app",
    components: {
        TopCinema,
        MenuCinema,
        BotCinema
    }
}

</script>
<style>
@import "../../assets/plugins/simplebar/css/simplebar.css";
@import "../../assets/plugins/perfect-scrollbar/css/perfect-scrollbar.css";
@import "../../assets/plugins/metismenu/css/metisMenu.min.css";
@import "../../assets/css/pace.min.css";
@import "../../assets/css/bootstrap.min.css";
@import "../../assets/css/bootstrap-extended.css";
@import url("https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap");
@import "../../assets/css/app.css";
@import "../../assets/css/icons.css";
@import "../../assets/css/dark-theme.css";
@import "../../assets/css/semi-dark.css";
@import "../../assets/css/header-colors.css";
@import url("https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css");
</style>