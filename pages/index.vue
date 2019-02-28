<template>
  <b-container fluid>
    <div class="mega-head">
      <div class="effects">
        <effects />
      </div>
      <b-container>
        <section class="container">
          <div>
          test
            <logo />
            <h1 class="title">
              stargaze2
            </h1>
            <h2 class="subtitle">
              We Shine, You Gazed.
            </h2>
            <div class="links">
              <a
                href="https://nuxtjs.org/"
                target="_blank"
                class="button--green"
              >Documentation</a>
              <a
                href="https://github.com/nuxt/nuxt.js"
                target="_blank"
                class="button--grey"
              >GitHub</a>
            </div>
          </div>
        </section>
      </b-container>
    </div>
  <div class="alert alert-primary" role="alert">
    This is a primary alert—check it out!
  </div>
  </b-container>
</template>
<script>
import Logo from '~/components/Logo.vue'
import Planetarium from '~/components/Planetarium.vue'

export default {
  components: {
    Logo,
    'effects': Planetarium
  }
}
</script>

<style lang="scss">
.mega-head {
  position: relative;

  .effects {
    position: absolute;
    top: 0;
    left: 0;
  }
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
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
