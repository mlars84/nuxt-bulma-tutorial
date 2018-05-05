<template>
  <section class="container">
    <div>
      <h1 class="title">
        Hello World
      </h1>
    </div>
  </section>
</template>

<script>
import AppLogo from '~/components/AppLogo.vue'

export default {
  components: {
    AppLogo
  }
}
</script>

<style lang="scss">
.title {
  color: $info;
}
</style>
