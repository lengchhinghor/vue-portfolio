<template>
  <div style="background-color: #000; padding: 50px 100px; color: #fff;">
    <v-row>
        <v-col class="6">
            <div>
                <h3 style="font-weight: 300">Latest Works</h3>
                <p style="color: grey">Prefer solution for digital experience</p>
            </div>
            <div class="my-10">
                <img src="https://img.freepik.com/premium-vector/16-pages-minimalist-photography-portfolio-design_123371-191.jpg?w=2000" style="width: 100%;" alt="">
            </div>
            <div class="mx-10 projects">
                <a href="#">ALL PROJECTS</a>
                <p class="mt-5">Some projects not allow publish by NVA, If you want to see more, <a href="#">Contact</a> </p>
            </div>
        </v-col>
        <v-col class="6">
            <div>
                <img src="https://elementor.com/marketing/wp-content/uploads/sites/9/2018/10/RhplP2v-1024x682.png" alt="" style="width: 100%;">
            </div>
            <div class="mt-5">
                <img src="https://s3-torquehhvm-wpengine.netdna-ssl.com/uploads/2020/11/wordpress-theme-directory-1024x682.png" alt="" style="width: 100%;">
            </div>
        </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
    name: "DoneWork"
}
</script>

<style scoped>
.projects a {
    color: rgb(105, 240, 174);
    text-decoration: underline;
    font-size: 20px;
}
.projects p a {
    font-size: 16px;
}
</style>