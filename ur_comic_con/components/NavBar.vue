<template>
  <header class="header">
    <h1 class="title">UR COMIC CON</h1>
    <ul>
      <li>
        <nuxt-link to="/">HOME</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/about">ABOUT</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/contact">CONTACT</nuxt-link>
      </li>
    </ul>
  </header>
</template>

<script>
export default {
  name: "NavBar"
};
</script>

<style>
.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 1rem;
  padding: 1rem;
  background: #fffc32;
}
.header .title {
  font-size: 2rem;
  color: #1573ff;
  margin-left: 1rem;
}
.header ul {
  display: flex;
}
.header a {
  display: inline-block;
  color: #1573ff;
  margin-right: 0.5rem;
}
</style>