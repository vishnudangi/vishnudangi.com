<template>
  <footer class="top-nav-section">
    <nav>
    <ul>
  <li><router-link  to="/" exact>Home</router-link></li>
  <li><router-link  to="/about" exact>About Me</router-link></li>
  <li><router-link  to="/skills" exact>Skills</router-link></li>
  <li><router-link  to="/projects" exact>Projects</router-link></li>
  <li><router-link  to="/articles" exact>Articles</router-link></li>
  <li><router-link  to="/contact" exact>Contact Me</router-link></li>
</ul>
</nav>
  </footer>
</template>

<script>
export default {
  name: 'header'
}
</script>

<style>
.top-nav-section{
  position: fixed;
  top: 0;
  width: 100%;
}
nav{
  text-align: center;
}
ul {
  height: 70px;
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    width: 100%;
    height: 100%;
    background-color: #2098D1;
}
li {
  display: inline-block;
  margin: 5px 10px;
}

li a {
    display: block;
    color: #ffffff;
    font-size: 15px;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

li a:hover {
     color: #06BC9B
}
li .router-link-active {
  color: #06BC9B;
  border-bottom: 1px solid #06BC9B;
}
</style>
