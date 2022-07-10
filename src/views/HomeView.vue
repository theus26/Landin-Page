<template>
  <div class="home">
  <Header/>
  <MainVue />
 <FooterVue/>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '@/components/Header.vue'
import FooterVue from '@/components/Footer.vue'
import MainVue from '@/components/Main.vue'

export default {
  name: 'HomeView',
  components: {
    Header,
    FooterVue,
    MainVue
  }
}
</script>
