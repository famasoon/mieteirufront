<template>
  <section class="hero is-primary">
    <div class="hero-body">
      <div class="container">
        <h1 class="title">{{ name }}</h1>
        <h2 class="subtitle">Result</h2>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Banner',
  props: ['name']
}
</script>
