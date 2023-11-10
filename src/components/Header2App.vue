<template>
    <div class="height-black d-flex padding">

        <img :src="thumb" :alt="type">
        <span>{{ series }} </span>



    </div>
</template>

<script>
export default {
    name: 'Header2App',
    props: {
        thumb: String,
        series: String,
        type: String

    }
}
</script>

<style lang="css" scoped>
.height-black {
    height: 150px;
    background-color: black;
}

img {
    width: 100px;
}

.padding {
    padding-left: 300px;
    padding-right: 400px;
}
</style>