<template>
    <div class="header">
        <div class="header_logo">
            <img class="header_img" src="../assets/img/logo.svg" alt="logo">
        </div>
        <div class="header_menu">
            <a class="header_link">Алматы</a>
            <a class="header_link">Астана</a>
            <a class="header_link">Другие</a>
            <a class="header_link">О НАС</a>
        </div>
    </div>
</template>

<script>
export default {
    name: "MyHeader"
}


</script>

<style scoped>
.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 0 352px;
    position: fixed;
    top: 0;
    z-index: 999;
    width: 1216px;
    height: 152px;
}

.header_link {
    font-family: 'Montserrat';
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    line-height: 22px;
    /* identical to box height */

    text-transform: uppercase;
    margin-right: 49px;
}
</style>