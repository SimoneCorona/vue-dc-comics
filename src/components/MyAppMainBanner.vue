<template>
    <div>
        <div class="main-banner">
            <img src="../assets/img/jumbotron.jpg" alt="">
        </div>
        
    </div>
</template>

<script>
export default {
    name: 'MyAppBanner',
}
</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/variables.scss";

.main-banner{
    img{
        width: 100%;
    }
}

</style>