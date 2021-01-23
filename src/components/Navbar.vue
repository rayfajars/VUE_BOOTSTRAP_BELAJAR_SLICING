<template>

  <b-navbar toggleable="lg" type="light">
		<b-container>
    <b-navbar-brand class="nav-brand" href="#">RayFaj</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-item href="#">Home</b-nav-item>
				<b-nav-item href="#">Pricing</b-nav-item>
				<b-nav-item href="#">Features</b-nav-item>
				<b-nav-item href="#">About</b-nav-item>
				<b-button variant="primary" class="tombol">Join Us</b-button>
     
      </b-navbar-nav>

      
    </b-collapse>
		</b-container>
  </b-navbar>


  
</template>

<script>
export default {
    name : "Navbar"

}
</script>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Viga&display=swap');





</style>