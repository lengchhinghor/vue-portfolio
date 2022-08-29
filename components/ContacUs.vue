<template>
  <div style="background-color: #000; padding: 50px 100px">
    <v-row>
        <v-col cols="6" style="color: #fff">
            <p>Let's make something amazing toghtether. <br/>Start by <a href="#" style="color: rgb(105, 240, 174);">saying hi</a></p>
        </v-col>
        <v-col cols="6" style="color: #fff">
            <p style="color: grey">Informations</p>
            <p style="color: grey">No. 132, (Corner) Norodom Blvd and Street 294, 12301</p>
            <h1 style="font-weight: 300;">mr.example@gmail.com</h1>
            <ul class="mt-5">
                <li>
                    <a href="#">Service</a>
                </li>
                <li>
                    <a href="#">Works</a>
                </li>
                <li>
                    <a href="#">Note</a>
                </li>
                <li>
                    <a href="#">Contact</a>
                </li>
                <li>
                    <a href="#">About</a>
                </li>
            </ul>
            <div class="mt-5">
                <v-icon class="mr-5" color="#fff">mdi-facebook</v-icon>
                <v-icon class="mr-5" color="#fff">mdi-github</v-icon>
                <v-icon class="mr-5" color="#fff">mdi-linkedin</v-icon>
            </div>
        </v-col>
    </v-row>
    <v-row class="d-flex justify-center mt-10">
        <p style="color: grey; font-size:10px;">2022/08/29. All right reserve</p>
    </v-row>
  </div>
</template>

<script>
export default {
    name: "ContactUs"
}
</script>

<style scoped>
    ul {
        margin: 0;
        padding: 0;
    }
    ul li {
        list-style: none;
    }
    ul li a {
        color: #fff;
    }
    ul li:hover {
        text-decoration: underline;
    }
</style>