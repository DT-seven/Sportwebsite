<template>
  <Header />
  <Content />
  <Footer />
</template>

<script>
import Header from './Layout/Header.vue'
import Content from './Layout/Content.vue'
import Footer from './Layout/Footer.vue'
export default {
  name: 'Home',
  components:{
    Header,
    Content,
    Footer
  }
}
</script>
<style >

</style>