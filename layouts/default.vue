<template>
    <div>
      <Header />
        <Nuxt />
      <Footer/>
    </div>
</template>

<style>

</style>
<script lang="ts">
import Header from "~/components/Header.vue"
import Footer from "~/components/Footer.vue"
export default {
  components:{
    Header,
    Footer
  }
}
</script>