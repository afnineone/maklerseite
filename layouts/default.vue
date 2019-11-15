<template>
  <div class="p-5">
    <NavBar />
    <nuxt />
    <Footer />
  </div>
</template>

<script>
import NavBar from '../components/NavBar.vue'
import Footer from '../components/Footer.vue'

export default {
  components: {
    NavBar,
    Footer
  },
  data () {
    return {
      title: 'Mec World!'
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        // hid is used as unique identifier. Do not use `vmid` for it as it will not work
        { hid: 'description', name: 'description', content: 'My custom description' },
        { hid: 'noindex', name: 'robots', content: 'noindex' }

      ]
    }
  }
}
</script>
