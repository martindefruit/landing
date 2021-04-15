<template>
  <div class="p-0">
    <div>
      <div class="container p-0">
        <Navbar />
        <Header />
      </div>
      <div id="jobs" class="container-fluid p-0">
        <Banner />
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
h1, h2, h3, h4 {
  font-family:
    'Assistant',
    'Source Sans Pro',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
    color: #000a3e;
}

p, a, li {
  font-family: 'Roboto Condensed', sans-serif;
  color: #323f85;
}

h4 {
  opacity: .7;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
<style>
@import url('https://fonts.googleapis.com/css2?family=Assistant:wght@800&family=Roboto+Condensed&display=swap');
</style>
CSS rules to specify families

font-family: 'Assistant', sans-serif;
