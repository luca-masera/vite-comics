<template>
    <main>
        <div class="height-black">
            <h2>Content goes here </h2>
        </div>
        <div class="height-blu">
            <ul>
                <li v-for="(card, index) in listCard">

                    {{ card.text.img }}

                </li>

            </ul>

        </div>
    </main>
</template>

<script>
export default {
    name: 'MainApp',
    data() {

        return {
            listCard: [

                {
                    img: '/images/buy-comics-digital-comics',
                    text: 'DIGITAL COMICS'
                },
                {
                    img: '/images/buy-comics-mercandise',
                    text: 'DC MERCANDISE'
                },
                {
                    img: '/images/buy-comics-digital-comics',
                    text: 'DIGITAL COMICS'
                },
                {
                    img: '/images/buy-comics-shop-locator',
                    text: 'SHO LOCATOR'
                }, {
                    img: '/images/buy-comics-subscriptions',
                    text: 'SUBSCRIPTIONS'
                },
            ]


        }
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
</style>
