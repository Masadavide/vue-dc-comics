<template>
    <div class="box">
        <img :src="thumb" alt="">
        <h3>
            {{series}}
        </h3>
    </div>
</template>

<script>
export default {
    name: "fumetto",
    props:{
        "thumb": String,
        "price": String,
        "series": String,
        "type": String
    }
}
</script>

<style>
.box{
    width: calc(90% / 6);
}
h3{
    width: 100%;
    font-size: 20px;
    margin-top: 10px;
}
</style>