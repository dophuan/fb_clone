<template>
    <div class="form-group">
        <input type="text" class="searchbox" placeholder='$t("searchbox.placeholder")'>
    </div>
</template>

<script>
    export default {
        name: 'SearchBox'
    }
</script>

<style lang="scss" scoped>
.searchbox {
    width: 100%;
    min-width: 45px;
    height: 40px;
    border-radius: 45px;
    background-color: #f1f2f5;
    color: #7f8285;
}
</style>