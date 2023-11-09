<template>
    <footer>
        <div class="d-flex justify-content-between heigth padding-left  ">
            <div class="d-flex">
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
            </div>


            <div class="d-flex justify-content-end">
                <img class="img-logo" :src="'/images/dc-logo-bg.png'" alt="">
            </div>
        </div>
        <div class="d-flex justify-content-between align-items-center padding-left heigth-footer">
            <div>
                <button type="button" class="btn btn-secondary btn-lg border border-primary">SIGN-UP NOW!</button>

            </div>
            <div class="d-flex">
                <h4>FOLLOW US</h4>
                <div class="ps-4">

                    <img class="img-icons" :src="'/images/footer-facebook.png'" alt="">
                    <img class="img-icons" :src="'/images/footer-twitter.png'" alt="">
                    <img class="img-icons" :src="'/images/footer-youtube.png'" alt="">
                    <img class="img-icons" :src="'/images/footer-pinterest.png'" alt="">
                    <img class="img-icons" :src="'/images/footer-periscope.png'" alt="">
                </div>
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

.heigth-footer {
    height: 150px;
    background-color: grey
}

.img-logo {
    width: 15vw;
    height: 15vw;
}

.img-icons {
    width: 40px;
    background: aliceblue;
    padding: 5px;
}

.padding-left {
    padding-right: 400px;
    padding-left: 300px;

}

li {

    color: white;
    font-size: 12px;
    list-style: none;
}

h4 {
    color: blue
}
</style>