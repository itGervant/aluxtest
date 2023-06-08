<template>
    <div class="wrapper">
        <MyHeader />
        <img class="vector" src="../assets/img/firstvector.svg">
        <img class="secondvector" src="../assets/img/secondvector.svg">
        <img class="thirdvector" src="../assets/img/thirdvector.svg">
        <img class="forthvector" src="../assets/img/forthvector.svg">
        <img class="fifthvector" src="../assets/img/fifthvector.svg">
        <img class="redvector" src="../assets/img/redvector.svg">
        <div class="vector-container">
            <img class="sixvector" src="../assets/img/sixvector.svg">
            <img class="reddot" src="../assets/img/reddot.svg">
            <img class="yellowdot" src="../assets/img/yellow.svg">
            <img class="main" src="../assets/img/main.svg">
            <img class="redline" src="../assets/img/redvector.svg">
            <img class="yellowEllipse" src="../assets/img/yellowEllipse.svg">        
        </div>
        <div class="banner_text">
            <div class="banner_title">АЛМАТЫ</div>
            <div class="banner_subtitle">прогулка по «немецкой» истории города</div>
        </div>    
    </div>
</template>

<script>
import MyHeader from './MyHeader.vue';
export default {
    name: 'MyBanner',
    components: {MyHeader}
}

</script>

<style scoped>

.main {
    margin: 27px 73px 40px 31px;
    position: relative;
    z-index: 2;
}
.wrapper {
    background: #F9F7F3;
    height: 850px;
    position: relative;
    overflow: hidden;
    width: 100vw;
}
.banner_text {
    position: absolute;
width: 436px;
height: 119.3px;
left: 369px;
top: 422px;
} 


.reddot {
    position: absolute;
width: 48px;
height: 49px;
left: 61px;
top: 246px;
z-index: 5;
}

.yellowdot {
    position: absolute;
width: 105px;
height: 104px;
left: 0px;
top: 262px;
z-index: 4;
}

.redline {
    position: absolute;
    height: 116.77460789423041px;
width: 116.15447543149541px;
left: 128.56396484375px;
top: 9.901504516601562px;
border-radius: 0px;
z-index: 6;
transform: rotate(79.57deg)
}
.vector {
    position: absolute;
width: 1559.97px;
height: 735.37px;
left: -68.15px;
top: 162.36px;
overflow: hidden;
}

.secondvector {
    position: absolute;
width: 531.91px;
height: 387.74px;
left: -47.77px;
top: 517.26px;
}

.thirdvector {
    position: absolute;
width: 513.76px;
height: 685.59px;
left: 1500.67px;
top: -27.58px;
}

.forthvector{
    position: absolute;
width: 257.56px;
height: 177.43px;
left: 1527.05px;
top: 736.65px;
}

.fifthvector  {
    position: absolute;
width: 273.28px;
height: 205.96px;
left: 599.3px;
top: 757.05px;
}

.vector-container {
position: relative;
width: 725px;
height: 536px;
display: flex;
top: 241px;
left: 898px;


}
.sixvector {
    position: absolute;
width: 417px;
height: 387px;
left: 3px;
top: 101px;
}

.redvector {
    position: absolute;
    left: 1120px;
top: 290px;
width: 500px;
height: 500px;


}

.yellowEllipse {
    position: absolute;
width: 119.75px;
height: 125.53px;
left: 266.51px;
top: 0px;
z-index: 2;
}

</style>