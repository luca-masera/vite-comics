<template>
    <main class="d-flex heigth align-items-center">
        <div class="padding ">
            <img :src="'/images/dc-logo.png'" alt="">
        </div>
        <div>
            <ul class="nav">
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" href="#">Link</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled" aria-disabled="true">Disabled</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link disabled active" aria-current="page" href="#">Active</a>
                </li>
            </ul>

        </div>


    </main>
</template>

<script>

export default {
    name: 'HeaderApp'

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
</style>