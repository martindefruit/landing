<template>
  <div class="bg-photo">
    <b-jumbotron fluid="true" class="message">
      <h1 class="text-center">Let's build the next big thing.</h1>
    </b-jumbotron>
    <b-card-group class="w-75 mx-auto negative-m" deck>
      <b-card>
         <b-card-title>
         Front-End Web Developer
        </b-card-title>
        <b-card-text>
          Full-Time, Barcelona
        </b-card-text>
        <b-card-text class="card-text-h">
          We are looking for a Front-End Web Developer with proficiency in HTML5, CSS3 and JavaScript to join our team to work on the development the front-end layer of our applications and internal tools, based on the Vue.js framework, taking into account standards, compatibility between browsers and mobile devices.

        </b-card-text>
        <b-button v-b-modal.modal-1 variant="primary" class="w-100">See More</b-button>
      </b-card>
        <b-card>
         <b-card-title>
         Full Stack Java Software Engineer
        </b-card-title>
        <b-card-text>
          Full-Time, Barcelona
        </b-card-text>
        <b-card-text class="card-text-h">
         We are looking for a well-rounded Full Stack Java Software Engineer to join our engineering team. The ideal candidate would be a passionate developer who takes pride in what they do and who will be able to contribute to a growing number of exciting applications and tools to disrupt the real estate industry.
        </b-card-text>
         <b-button v-b-modal.modal-2 variant="primary" class="w-100">See More</b-button>
      </b-card>
    </b-card-group>
    <About />
    <Modals />


    <div class="w-75 mx-auto">
     <Footer />
    </div>
  </div>

</template>

<style>
  .card {
    border: none;
    box-shadow: -2px 3px 20px 8px rgb(90 105 181 / 10%);
  }
  .message {
    height: 350px;
    background-color:#000A3E;
    padding-top: 100px;
  }
  .message h1 {
    color: white;
    font-size: x-large;
  }
  .card-text-h {
    min-height: 160px;
  }
  .negative-m {
    margin-top: -150px;
  }
  .bg-photo {
    /*background-image: url(/_nuxt/assets/foot-image.png);*/
    background-size: contain;
    background-repeat: no-repeat;
    background-position-x: 630px;
    background-position-y: 232px;
  }

  .btn-primary {
    background-color: #7e63bc;
    border-color: #7e63bc;
  }
  .btn-primary:hover {
    background-color: transparent;
    color: #7e63bc;
    border-color: #7e63bc;
  }
</style>
