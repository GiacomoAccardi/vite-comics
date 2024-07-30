<script>
export default {
    props: {
        imagePath: String,
        title: String,
    }
}
</script>

<template lang="">
    <div class="col-md-4 col-xl-2">
        <img :src="imagePath" :alt="title">
        <h5>{{title}}</h5>
    </div>
</template>

<style lang="scss" scoped>
    img{
        max-width: 200px;
        height: 300px;
        margin-bottom: 10px;
        object-fit: fill;
    }
    h5{
        margin-bottom: 30px;
    }
</style>