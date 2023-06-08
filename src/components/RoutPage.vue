<template>
    <div class="container">
        <h2>УВЛЕКАТЕЛЬНЫЙ МАРШРУТ ПО ГОРОДУ</h2>
        <div class="rout_items">
            <div class="rout_item">
                <img class="rout_back" src="../assets/img/redvector.svg">
                <div class="rout_image">
                    <img src="../assets/img/image1.svg">
                </div>
                <img class="rout_icon" src="../assets/img/yellow.svg">
                <h2 class='rout_title'>РОЩА БАУМА</h2>
            </div>
            <div class="rout_item2">
                <img class="rout_back" src="../assets/img/redvector.svg">
                <div class="rout_image">
                    <img src="../assets/img/image1.svg">
                </div>
                <img class="rout_icon" src="../assets/img/yellow.svg">
                <h2 class='rout_title'>РОЩА БАУМА</h2>
            </div>
            <div class="rout_item3">
                <img class="rout_back" src="../assets/img/redvector.svg">
                <div class="rout_image">
                    <img src="../assets/img/image1.svg">
                </div>
                <img class="rout_icon" src="../assets/img/yellow.svg">
                <h2 class='rout_title'>РОЩА БАУМА</h2>
            </div>
            <div class="rout_item4">
                <img class="rout_back" src="../assets/img/redvector.svg">
                <div class="rout_image">
                    <img src="../assets/img/image1.svg">
                </div>
                <img class="rout_icon" src="../assets/img/yellow.svg">
                <h2 class='rout_title'>РОЩА БАУМА</h2>
            </div>
            <div class="rout_item5">
                <img class="rout_back" src="../assets/img/redvector.svg">
                <div class="rout_image">
                    <img src="../assets/img/image1.svg">
                </div>
                <img class="rout_icon" src="../assets/img/yellow.svg">
                <h2 class='rout_title'>РОЩА БАУМА</h2>
            </div>
        </div>
        <VectorPage />
    </div>
</template>

<script>

import VectorPage from './VectorPage.vue';
export default {
    name: 'RoutPage',
    components: { VectorPage }
}

</script>

<style>
.container {
    margin: 157px 376px;
    position: relative;

}

.rout_item {
    width: 388px;
    height: 420px;
    position: relative;
    top: 72px;
    left: 33px;

}

.rout_item2 {
    width: 388px;
    height: 420px;
    position: absolute;
    top: 132px;
    left: 581px;


}

.rout_item3 {
    width: 388px;
    height: 420px;
    position: absolute;
    top: 545px;
    left: 26px;
}

.rout_item4 {
    width: 388px;
    height: 420px;
    position: absolute;
    top: 601px;
    left: 766px;
}

.rout_item5 {
    width: 388px;
    height: 420px;
    position: absolute;
    top: 902px;
    left: 321px;
}

.rout_item6 {
    width: 388px;
    height: 420px;
    position: absolute;
    top: 1092px;
    left: 581px;
}

.rout_back {
    height: 360px;
    width: 360px;
    position: absolute;
    top: 0;
    left: 0;

}

.rout_image {
    position: absolute;
    width: 264px;
    height: 264px;
    left: 43px;
    top: 43px;
}

.rout_icon {
    position: absolute;
    top: 45px;
    left: 57px;
    height: 57px;
    width: 58px;


}

.rout_title {
    position: absolute;
    width: 159px;
    height: 31px;
    left: 107px;
    top: 369px;
}
</style>