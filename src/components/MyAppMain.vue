<template>
    <div class="wrapper">
        <div class="productsInfo">
            <img :src="thumb" alt="">
            <p>{{ series }}</p>
        </div>
    </div>
        
    
</template>

<script>
export default {
    name: 'MyAppMain',

    props: {
        thumb: String,
        series: String,
    }
}
    

</script>

<style scoped lang="scss">
@import "../style/common.scss";
@import "../style/variables.scss";


.wrapper{
    width: calc(100% / 6);
    

    .productsInfo{
        margin: 0 1rem;

        img{
            width: 100%;
            
        }
        p{
            font-weight: 300;
            font-size: 0.8rem;
            color: white;
        }
    }
}





</style>