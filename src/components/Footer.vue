<template>
  <footer class="footer-section">
    <div class="main-content">
      <a class="social-contact" href="https://github.com/vishnudangi" target="_blank">
      <i class="fa fa-2x fa-github-square"></i>
      </a>
      <a class="social-contact" href="https://www.linkedin.com/in/vishnu-dangi-77b10037/" target="_blank">
      <i class="fa fa-2x  fa-linkedin-square"></i>
      </a>
      <a class="social-contact" href="https://twitter.com/vishnudangi16" target="_blank">
      <i class="fa fa-2x fa-twitter-square"></i>
      </a>
      <a class="social-contact" href="https://www.facebook.com/vishnu.dangi" target="_blank">
      <i class="fa fa-2x fa-facebook-square"></i>
      </a>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'footer'
}
</script>
<style>
.footer-section {
  position: fixed;
  bottom: 0;
  background-color: #080b11;
  width: 100%;
  height: 100px;
  color: #ffffff;
  text-align: center;
}
.main-content {
  padding: 35px;
}
.social-contact {
  text-decoration: none;
  color: inherit;
  margin: 20px 15px;
}
</style>
