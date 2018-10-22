<template>
  <div>
    <Header/>
    <main class="content-section">
      <router-view></router-view>
    </main>
    <Footer/>
  </div>
</template>
<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'
export default {
  name: 'app',
  components: {
    Header,
    Footer
  }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.content-section{
  margin: 75px 10px 10px 100px;
}
</style>
