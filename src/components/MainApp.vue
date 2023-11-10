<template>
    <main>
        <div class="height-black">
            <img :src="thumb" :alt="type">

            <h2>{{ series }}</h2>
        </div>
        <div class="height-blu ">
            <ul class="d-flex padding align-items-center">
                <li>
                    <img :src="'/images/buy-comics-digital-comics.png'" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img :src="'/images/buy-comics-merchandise.png'" alt="">
                    <span>DC MERCHANDISE</span>

                </li>
                <li>
                    <img :src="'/images/buy-comics-digital-comics.png'" alt="">
                    <span>DIGITAL COMICS</span>
                </li>
                <li>
                    <img :src="'/images/buy-comics-shop-locator.png'" alt="">
                    <span>SHOP LOCATOR</span>
                </li>
                <li>
                    <img :src="'/images/buy-comics-subscriptions.png'" alt="">
                    <span>SUBSCRIPTIONS</span>
                </li>




            </ul>

        </div>
    </main>
</template>

<script>
import { stringifyExpression } from '@vue/compiler-core';

export default {
    name: 'MainApp',

    props: {
        thumb: String,
        series: String,
        type: String

    }

}
</script>

<style lang="css" scoped>
main {
    height: 300px;
    background-color: blue;
}

.height-black {
    height: 150px;
    background-color: black;
}

.height-blu {
    height: 150px;
    background-color: blue;
}

h2 {
    color: white;
    padding-left: 300px;
    padding-top: 50px;

}

li {
    list-style: none;
    padding: 40px;
}

.padding {
    padding-left: 300px;
    padding-top: 15px;


}

span {
    color: white;
}

img {
    width: 45px;
}
</style>
