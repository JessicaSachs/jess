<template>
  <main id="app">
      <section class="section">
        <h1 class="name">Jessica Sachs</h1>
        <h2 class="job">Staff Engineer @ Intent</h2>
        <p>A caffeine-based lifeform, circus nerd, VueJS afficionado, and VueVixen.</p>
        <p>⚠️ Site under construction</p>
        <section>
          <h3>Links</h3>
          <ul>
            <li><a href="https://twitter.com/_jessicasachs">@_jessicasachs</a></li>
            <li><a href="mailto:jess+web@jessicasachs.io?subject=Hey, Jess!">Email</a></li>
          </ul>
        </section>


        <!--<div class="activities">-->
          <!--<div>☕ Caffeine-based lifeform</div>-->
          <!--<div>🎪 Circus nerd</div>-->
          <!--<div><img class="vue-spock" src="./assets/vue-spock.svg"/> VueJS afficionado</div>-->
          <!--<div><img class="vue-vixen" src="./assets/vue-vixen.png"/> Vue Vixen</div>-->
        <!--</div>-->
      </section>
  </main>
</template>

<script>
import 'normalize.css'

export default {
  name: 'app',
  components: {
  }
}
</script>

<style lang="scss">

  .job {
    font-size: 2rem;
  }
  .name {
    font-size: 4.242rem;
    line-height: 4.5rem;
    margin-top: 3rem;
    font-weight: 700;
  }





  .section {
    margin: 0 auto;
}

.vue-spock {
    width: 1.1em;
}

.vue-vixen {
    width: 1.1em;
}

.activities {
    clear: both;
    text-align: left;
}

.jess {
    margin: 0 auto;
    border-radius: 100%;
    background-image: url(./assets/jess.jpg);
    width: 100px;
    height: 100px;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    box-shadow: 1px 2px 3px rgba(0,0,0,.4);
}

h1, h2, h3, h4, h5, h6, span {
  margin: 0;
}

html, body {
    margin: 0;
    width: 100%;
    height: 100%;
}

  @media only screen and (max-width: 812px) {
    body {
      margin: 16px;
    }
  }

#app {
    /*width: 800px;*/
    margin: 100px auto 0 auto;
  text-align: left;
  font-family: -apple-system, system-ui, BlinkMacSystemFont, 'Segoe UI', Roboto,
  Ubuntu, 'Helvetica Neue', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  font-size: 1.3rem;

  /*margin-top: 60px;*/
}
</style>
