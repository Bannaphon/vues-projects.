<template>
  <navbar />
  <section class="home">

    <div class="image">
        <img src="images/day6-.png" alt="">
    </div>

    <div class="content">
        <h3>hi, {{name}}</h3>
        <span>{{motto}}</span>
        <p>{{content}}</p>
        <a href="about.html" class="btn"> about me <i class="fas fa-user"></i> </a>
    </div>

</section>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: { Navbar },
  data() {
      return {
        name: 'Bannaphon Kongthip',
        motto: 'Fortune favors the prepared mind.',
        content: 'im study at Bankok University in Engineer',
      }
 }

}
</script>

<style>

</style>