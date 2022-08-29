<template>
    <div class="mt-10">
        <section id="service" class="service">
            <v-row>
                <v-col cols="6">
                    <v-card class="text-center green accent-2 py-1" width="200" style="border-radius: 20px;">Front-End Developer</v-card>
                    <div class="content my-5 ml-5">
                      <h3>Talk is cheap.<br/>Show me the code.</h3>
                      <p class="my-5 mb-15">I design the code beautifuly simple things,and I love what I do</p>
                      <a href="#">LET'S CHAT</a>
                    </div>
                    <div class="experience d-flex my-15" style="color: grey">
                      <div class="group-content d-flex">
                        <h4>12</h4>
                        <p>YEARE<br/>XPERIENCE</p>
                      </div>
                      <div class="group-content d-flex">
                        <h4>12</h4>
                        <p>PROJECT COMPLETED<br/>ON 18 COUNTRIES</p>
                      </div>
                    </div>
                </v-col>
                <v-col cols="6">
                  <div class="technology">
                    <v-card class="text-center green accent-2 py-1" width="200" style="border-radius: 20px">Use Technologies</v-card>
                    <div class="list my-5 d-flex flex-column" style="padding-top: 20%">
                      <div class="d-flex justify-space-between mb-5">
                        <div style="border-radius: 50%;">
                          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/27/PHP-logo.svg/2560px-PHP-logo.svg.png" alt="">
                        </div>
                        <div style="border-radius: 50%;">
                          <img src="https://www.dariawan.com/media/images/tutorial-spring-logo.width-1024.png" alt="">
                        </div>
                        <div style="border-radius: 50%;">
                          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Laravel.svg/1200px-Laravel.svg.png" alt="">
                        </div>
                      </div>
                      <div class="d-flex justify-space-between">
                        <div style="border-radius: 50%;">
                          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/61/HTML5_logo_and_wordmark.svg/512px-HTML5_logo_and_wordmark.svg.png" alt="">
                        </div>
                        <div style="border-radius: 50%;">
                          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d5/CSS3_logo_and_wordmark.svg/1200px-CSS3_logo_and_wordmark.svg.png" alt="">
                        </div>
                        <div style="border-radius: 50%;">
                          <img src="https://quintagroup.com/cms/js/js-image/javascript-logo.png/@@images/8c64c4b9-4e1c-4c26-9b5e-78d85e3130a9.png" alt="">
                        </div>
                      </div>
                    </div>
                  </div>
                </v-col>
            </v-row>
        </section>
        <section id="work">
          <WorkExperience/>
        </section>
        <section id="done-work">
          <DoneWork/>
        </section>
        <section id="tesimonials">
          <ClientSay/>
        </section>
        <section id="contact">
          <ContacUs/>
        </section>
    </div>
</template>

<script>
import DoneWork from '~/components/DoneWork.vue';
import ClientSay from '~/components/ClientSay.vue';
import ContacUs from '~/components/ContacUs.vue';
export default {
    name: "IndexPage",
    components: { DoneWork, ClientSay, ContacUs }
}
</script>

<style scoped>
.service {
    background-color: rgb(45, 46, 50);
    /* min-height: 100vh; */
    color: #fff;
    padding: 50px 100px;
}
.service .content h3 {
  font-weight: 100;
  font-size: 30px;
}
.service .content p {
  color: grey;
}
.service .content a {
  text-decoration: underline;
  color: rgb(105, 240, 174);
}
.experience .group-content h4 {
  font-size: 52px;
  font-weight: 300;
  margin-top: -15px;
  margin-right: 10px;
}
.technology .list img {
  width: 70px;
}
</style>