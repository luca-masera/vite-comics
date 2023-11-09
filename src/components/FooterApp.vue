<template>
    <footer class="heigth padding-left ">
        <div class="d-flex  ">
            <div>
                <ul class="pt-4">
                    <li>
                        <h5>DC COMICS</h5>
                    </li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>
                        <h5>SHOP</h5>
                    </li>
                    <li>shop</li>
                    <li>shop</li>

                </ul>
            </div>
            <div>
                <ul class="pt-4">
                    <li>
                        <h5>DC COMICS</h5>
                    </li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>TV</li>
                    <li>shop</li>
                    <li>shop</li>

                </ul>
            </div>
            <ul class="pt-4">
                <li>
                    <h5>DC COMICS</h5>
                </li>
                <li>TV</li>
                <li>TV</li>
                <li>TV</li>

            </ul>


            <div class="d-flex justify-content-end">
                <img :src="'/images/dc-logo-bg.png'" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'FooterApp'
}
</script>

<style lang="css" scoped>
.heigth {
    height: 300px;
    background-image: url('/images/footer-bg.jpg')
}


img {
    width: 20%;
}


.padding-left {
    padding-left: 300px;
}

li {

    color: white;
    font-size: 12px;
    list-style: none;
}
</style>