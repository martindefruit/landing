<template>
<div>
  <b-jumbotron class="bg-image header mb-0" fluid="true">
      <p class="text-center"><span>Coming 2021</span></p>
      <h1 class="text-center">Reshaping the real estate<br>marketplace through tech.</h1>

  </b-jumbotron>
</div>
</template>

<style>
  .header {
    height: 60vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .header h1 {
    font-size: 3rem;
  }

  .bg-image {
    background-image: url(~/assets/foot-image.png);
    background-size: cover;
    background-position: center;
  }

  .header span {
    text-transform: uppercase;
    letter-spacing: 4px;
  }

  @media (max-width: 375px) {
    .header h1 {
      font-size: 2.6rem;
    }
  }

</style>
