<template>
    <header class="header">
        <div class="header-inner">
            <div id="header_title">
                <h1>Meow</h1>
                <p>tomioka miki's portfolio</p>
            </div>
            <div id="navbar">
                <ul>
                    <li><nuxt-link v-scroll-to="'body'" to>Home</nuxt-link></li>
                    <li><nuxt-link v-scroll-to="'#About_me'" to>About me</nuxt-link></li>
                    <li><nuxt-link v-scroll-to="'#Skills'" to>Skills</nuxt-link></li>
                    <li><nuxt-link v-scroll-to="'#Work'" to>Work</nuxt-link></li>
                    <li><nuxt-link v-scroll-to="'#Contact'" to>Contact</nuxt-link></li>
                </ul>
            </div>
            <div id="header_image">
                <img src="~/assets/images/neko1.jpg" alt="">
            </div>
        </div>
    </header>
</template>