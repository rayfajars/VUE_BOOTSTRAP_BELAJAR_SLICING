<template>
  <div class="home">
    <Navbar />
    <Jumbotron />

    <div class="container">
      <InfoPanel />
      <WorkingSpace />
      <Testimonial />
      <Footer />


    </div>
    
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Jumbotron from '@/components/Jumbotron.vue'
import Navbar from '@/components/Navbar.vue'
import InfoPanel from '@/components/InfoPanel.vue'
import WorkingSpace from '@/components/WorkingSpace.vue'
import Testimonial from '@/components/Testimonial.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    Jumbotron,
    Navbar,
    InfoPanel,
    WorkingSpace,
    Testimonial,
    Footer
  }
}
</script>
