<template>
    <main class="d-flex heigth align-items-center">
        <div class="padding ">
            <img :src="'/images/dc-logo.png'" alt="">
        </div>
        <div>
            <ul class="d-flex">
                <li class="p-10" v-for="(link, index) in list">
                    {{ link.text }}
                </li>

            </ul>
        </div>


    </main>
</template>

<script>

export default {
    name: 'HeaderApp',
    data() {

        return {
            list: [

                {
                    text: 'Characters',
                    url: '#'

                },
                {
                    text: 'Comics',
                    url: '#'
                },
                {
                    text: 'Movie',
                    url: '#'
                },
                {
                    text: 'Tv',
                    url: '#'
                },
                {
                    text: 'Games',
                    url: '#'
                },
                {
                    text: 'Video',
                    url: '#'
                },
                {
                    text: 'Shop',
                    url: '#'
                },
                {
                    text: 'Contacts',
                    url: '#'
                }
            ]

        }
    }

}
</script>

<style lang="css" scoped>
.padding {
    padding-left: 300px;
    padding-right: 300px;
}

.heigth {
    height: 150px;


}

li {
    list-style: none;
}

.p-10 {
    padding: 10px;
}
</style>
