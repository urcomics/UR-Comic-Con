<template>
  <div class="header">
      <h1 class="logo"> UR COMIC CON </h1>
    <div class="container">
        <Nuxt/>
    </div>
  </div>
</template>

<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  font-size: 1rem;
  line-height: 1.6;
  background: #1333bd;
}
a {
  color: #e83731;
  text-decoration: none;
}
.container {
  max-width: 1200px;
  overflow: hidden;
  padding: 1rem 2rem;
  margin-top: 5rem;
  color: #fee54d;
  text-align: center;
  font-size: 1rem;
  font-family: Helvetica;
  font-weight: 100;
}
.header {
  color: #1333bd;
  background: #fee54d;
  text-align: center;
  max-height: 10rem;
  padding: 2rem;
}
.logo{
  font-size: 5rem;
  font-family: 'Badaboom';
  font-weight: 600;
  text-shadow: 4px 4px #e83731;
}
</style>