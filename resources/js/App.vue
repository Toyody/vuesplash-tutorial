<template>
  <div>
    <header>
      <Navbar />
    </header>
    <main>
      <div class="container">
        <RouterView />
      </div>
    </main>
    <Footer />
  </div>
</template>

<script>
  import Navbar from './pages/Navbar.vue'
  import Footer from './pages/Footer.vue'

  export default {
    components: {
      Navbar,
      Footer
    }
  }
</script>