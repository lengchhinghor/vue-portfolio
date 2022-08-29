<template>
  <div style="background-color: #000; padding: 50px 100px;">
    <v-row>
        <v-col cols="6">
            <div class="card">
                <v-card class="my-6" color="rgb(45, 46, 50)" style="border-radius: 20px">
                    <v-card-title class="card-title my-n3">Design</v-card-title>
                    <v-card-text class="card-body my-n3">Create digital products with unique ideas</v-card-text>
                    <v-card-text class="card-footer my-n3">
                        <a href="#">10 PROJECTS</a>
                    </v-card-text>
                </v-card>

                <v-card class="my-6" color="rgb(45, 46, 50)" style="border-radius: 20px">
                    <v-card-title class="card-title my-n3">Back-End</v-card-title>
                    <v-card-text class="card-body my-n3">I develop Back-End fast website</v-card-text>
                    <v-card-text class="card-footer my-n3">
                        <a href="#">10 PROJECTS</a>
                    </v-card-text>
                </v-card>

                <v-card class="my-6" color="rgb(45, 46, 50)" style="border-radius: 20px">
                    <v-card-title class="card-title my-n3">Fronte-End</v-card-title>
                    <v-card-text class="card-body my-n3">I develop front-end coding super smooth</v-card-text>
                    <v-card-text class="card-footer my-n3">
                        <a href="#">10 PROJECTS</a>
                    </v-card-text>
                </v-card>
            </div>
        </v-col>
        <v-col cols="6" style="color: grey;">
            <p>Introduction</p>
            <div class="name">
                <h3>Hello! I'm Visal</h3>
                <p>Every great design begin with you an even better story</p>
            </div>
            <p class="mt-5">Since begining my journey as a freelance designer nearly 8 years ago, I've done remote work for agencies, consulted for startups, and collaboratted with talented people to create digital products, for both business and cosumer use. I'm quietly confident, naturally currious, and perpetually working on improving my chopsone design problem at a time.</p>
        </v-col>
    </v-row>
    <v-row style="color: #fff" class="d-flex justify-center pt-5">
        <div>
            <a href="#" class="mx-5">
                <v-icon>mdi-aws</v-icon>
            </a>
            <a href="#" class="mx-5">
                <v-icon>mdi-alphabetical-variant </v-icon>
            </a>
            <a href="#" class="mx-5">
                <v-icon>mdi-bio</v-icon>
            </a>
            <a href="#" class="mx-5">
                <v-icon>mdi-box</v-icon>
            </a>
        </div>
    </v-row>
  </div>
</template>

<script>
export default {
    name: "WorkExperience"
}
</script>

<style scoped>
.card .card-title {
    color: rgb(105, 240, 174) !important;
    font-weight: 300;
}
.card .card-body {
    color: grey;
}
.card .card-footer a {
    color: #fff;
    font-size: 18px;
    font-weight: 300;
    text-decoration: underline;
}
.name h3 {
    font-weight: 400;
    font-size: 30px;
    color: #fff;
}
.name p {
    color: #fff;
    font-size: 18px;
    margin-top: 20px;
}
a .v-icon {
    color: grey;
    font-size: 50px;
}

a .v-icon:hover {
    color: #fff;
}
</style>