<template>
    <div class="header">
        <img src="../../static/fb-log.png" class="logo" alt="Logo"/>
    </div>
</template>

<script>
    export default {
        name: "Navbar"
    }
</script>

<style lang="scss" scoped>
.header {
    width: 100%;
    height: 60px;
    background-color: #fff;
    box-shadow: none 5px 10px #888;
    display: flex;
    align-items: center;

    .logo {
        margin: 10px 10px 10px 16px;
        width: 40px;
        height: 40px;
        color: #1a77f2;
    }

    .search-box {
        border-radius: 45px;
        background-color: #eff2f5;
    }
}
</style>