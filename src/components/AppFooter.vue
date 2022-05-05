<template>
    <footer>
        <div id="blueBar">
            <a href="#">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                <h1>digital comics</h1>
            </a>
            <a href="#">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <h1>dc merchandise</h1>
            </a>
        </div>
        <div id="heroFooter">
            <div id="links">
                            <ul id="dcComics">
                <li>dc comics</li>
                <li v-for="n in 7" :key="n">
                    dc link
                </li>
            </ul>
            <ul id="shop">
                <li>shop</li>
                <li v-for="n in 2" :key="n">
                    shop link
                </li>
            </ul>
            <ul id="dc">
                <li>shop</li>
                <li v-for="n in 11" :key="n">
                    dc link
                </li>
            </ul>
            <ul id="sites">
                <li>shop</li>
                <li v-for="n in 5" :key="n">
                    sites link
                </li>
            </ul>
            </div>

        </div>
        <div id="socials">
            <a href="#">sign-up now!</a>
            <div id="followUs">
                <h1>follow us</h1>
                <ul>
                <li v-for="n in 5" :key="n">
                    <i class="fa-brands fa-facebook"></i>
                </li>
                </ul>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
    name: 'AppFooter'
}
</script>
