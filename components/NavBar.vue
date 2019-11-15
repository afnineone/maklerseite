<template>
  <ul class="navbar">
    <li class="mr-6">
      <nuxt-link to="/">
        Startseite
      </nuxt-link>
    </li>
    <li class="mr-6">
      <nuxt-link to="/privatkunden">
        Privatkunden
      </nuxt-link>
    </li>
    <li class="mr-6">
      <nuxt-link to="/geschäftskunden">
        Geschäftskunden
      </nuxt-link>
    </li>
    <li class="mr-6">
      <nuxt-link to="/About">
        Über Uns
      </nuxt-link>
    </li>
    <li class="mr-6">
      Link
    </li>
    <li class="mr-6">
      Disabled
    </li>
  </ul>
</template>

<script>
export default {}
</script>

<style scoped>
li{
  @apply text-green-600;
}

li:hover{
  @apply text-green-200;
}
</style>
