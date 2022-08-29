<template>
    <div id="app">
        <v-app id="inspire">
            <div>
                <v-app-bar color="black" dense dark style="position:fixed; z-index: 100">
                    <nuxt-link id="home" to="/">Home</nuxt-link>

                    <v-spacer></v-spacer>
                    <nuxt-link to="#service" class="px-5">
                        <v-app-bar-title>Service</v-app-bar-title>
                    </nuxt-link>
                    <nuxt-link to="#work" class="px-5">
                        <v-app-bar-title>Works</v-app-bar-title>
                    </nuxt-link>
                    <nuxt-link to="#tesimonials" class="px-5">
                        <v-app-bar-title>Note</v-app-bar-title>
                    </nuxt-link>
                    <nuxt-link to="#contact" class="px-5">
                        <v-app-bar-title>Contact</v-app-bar-title>
                    </nuxt-link>
                    <nuxt-link to="/about" class="px-5">
                        <v-app-bar-title>About</v-app-bar-title>
                    </nuxt-link>
                    <v-spacer></v-spacer>

                    <v-btn icon>
                        <v-icon>mdi-facebook</v-icon>
                    </v-btn>

                    <v-btn icon>
                        <v-icon>mdi-github</v-icon>
                    </v-btn>
                    <v-btn icon>
                        <v-icon>mdi-linkedin</v-icon>
                    </v-btn>
                </v-app-bar>
            </div>
            <main>
                <Nuxt />
            </main>
        </v-app>
    </div>
</template>

<script>
export default {
    name: 'DefaultLayout',
}
</script>

<style>
html {
  scroll-behavior: smooth;
}
#app {
    font-family: sans-serif;
}
a {
    text-decoration: none;
}
a.nuxt-link-exact-active {
    color: #00c58e;
}
.v-toolbar__title {
    font-size: 16px !important;
}
.home {
  color: #fff !important;
}
</style>