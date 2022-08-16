<template>
  <div class="container">
    <NavBar/>
    <nuxt/>
  </div>
</template>

<script>
import NavBar from "../components/NavBar";
export default {
  components: {
    NavBar
  }
};
</script>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 1rem;
  line-height: 1.6;
  background: #1573ff;
}
a {
  color: rgb(252, 95, 95);
  text-decoration: none;
}
ul {
  list-style: none;
}
.container {
  max-width: 1200px;
  overflow: hidden;
  padding: 1rem 2rem;
  color: #fffc32;
  text-align: center;
}
</style>