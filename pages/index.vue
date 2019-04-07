<template>
  <div>
    <index-banner />
    <url-input-form />
  </div>
</template>

<script>
import IndexBanner from '~/components/IndexBanner.vue'
import UrlInputForm from '~/components/UrlInputForm.vue'

export default {
  components: {
    IndexBanner,
    UrlInputForm
  }
}
</script>
