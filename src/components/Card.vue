<template>
    <div class="d-flex flex-column ">
        <img :src="thumb" :alt="type">
        <span>{{ series }} </span>
    </div>
</template>

<script>
export default {
    name: 'Card',
    props: {
        thumb: String,
        series: String,
        type: String

    }
}
</script>

<style lang="css" scoped>
img {
    width: 200px;
    height: 200px;
    padding: 10px;
}




span {
    color: white;
    width: 18px;
}
</style>