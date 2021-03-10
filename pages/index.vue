<template>
  <div class="container">
    <div class="content">
      <a href="/">
        <img class="logo" src="/images/logo.png" alt="The Artist Club Logo" />
      </a>
      <h2>Exposición de obras artísticas contemporáneas para el mundo</h2>
      <div class="links">
        <a
          href="https://play.google.com/store/apps/details?id=art.colombia.artclub"
          target="_blank"
        >
          <img
            class="google-play-logo"
            src="/images/google-play-logo.png"
            alt="Google Play Logo"
          />
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.links {
  padding-top: 15px;
}

.content {
  padding: 0 20px;
  .logo {
    width: 300px;
  }
  h2 {
    margin-top: 15px;
    margin-bottom: 15px;
  }
  .google-play-logo {
    width: 200px;
  }
}
</style>
