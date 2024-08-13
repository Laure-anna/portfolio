<template>
  <header>
    <!-- <div class="logo">logo</div> -->
    <a href="#"><img src="../assets/images/logo.png" alt=""></a>

    <nav class="nav">
      <a class="nav_link" href="#">A PROPOS</a>
      <a class="nav_link" href="#">COMPETENCES</a>
      <a class="nav_link" href="#">PROJETS</a>
      <a class="nav_link" href="#">CONTACT</a>
    </nav>
  </header>
</template>

<script setup></script>

<style scoped>

@font-face {
    font-family: "1942";
    src: url('../assets/police/1942.ttf') format('truetype'),
}

header {
  display: flex;
  justify-content: space-between;
  background: #ffffff99;
  padding: 18px 24px;
  position: sticky;
  box-shadow: 5px 5px 5px rgba(0,0,0,0.5);
}

img {
  width: 20px;
  padding-left: 30px;
}

.nav {
  display: flex;
  gap: 50px;
  font-family: "1942";
  padding-top: 15px;
  font-size: 25px;
  font-weight: 1000;
}

.nav a {
  transition: 0.8s;
}

.nav_link {
  color: black;
  text-decoration: none;
  
}

.nav a:hover, .navbar a.active {
    color: rgba(123, 7, 7, 0.977)
}
</style>
