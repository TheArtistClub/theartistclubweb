<template>
  <div class="container">
    <div class="content">
      <a href="/">
        <img class="logo" src="/images/logo.png" alt="The Artist Club Logo" />
      </a>
      <h2>Privacy Policy</h2>
      <p>
        Lorem Ipsum is simply dummy text of the printing and typesetting
        industry. Lorem Ipsum has been the industry's standard dummy text ever
        since the 1500s, when an unknown printer took a galley of type and
        scrambled it to make a type specimen book. It has survived not only five
        centuries, but also the leap into electronic typesetting, remaining
        essentially unchanged. It was popularised in the 1960s with the release
        of Letraset sheets containing Lorem Ipsum passages, and more recently
        with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
      </p>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="scss" scoped>
.container {
  margin: 20px auto;
  min-height: 100vh;
  text-align: center;
}

.content {
  padding: 0 20px;
  .logo {
    width: 200px;
  }
  h2 {
    margin-top: 15px;
    margin-bottom: 15px;
  }
}
</style>
