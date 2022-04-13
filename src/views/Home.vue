<template>
  <div>
    <Banner />
    <div class="main-container">
      <h1>Home</h1>
      <BurgerForm />
    </div>
  </div>
</template>

<script>
import Banner from '../components/Banner.vue'
import BurgerForm from '../components/BurgerForm'

export default {
  name: 'Home',
  components: {
    Banner,
    BurgerForm
  }
}
</script>