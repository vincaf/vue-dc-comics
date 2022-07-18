<template>
    <div class="comics-container">
        <img :src="imageUrl" :alt="title">
        <div class="title text-uppercase"> {{ title }} </div>
    </div>
</template>

<script>
export default {
    props:{
        'imageUrl': String,
        'title': String,
    }
}
</script>

<style lang="scss" scoped>
.comics-container{
    margin: 10px;
    width: calc((100% / 6) - 20px);

    img{
        width: 150px;
        height: 150px;
        object-fit: cover;
    }

    .title{
        color: #fff;
        margin-top: 5px;
        font-size: 12px;
    }
}

</style>