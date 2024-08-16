<template>

  <header>

    <a href="#"><img src="../assets/images/logo.png" alt="logo"></a>

    <nav class="nav">
      <a class="nav_link" href="#apropos">A PROPOS</a>
      <a class="nav_link" href="#competences">COMPETENCES</a>
      <a class="nav_link" href="#projets">PROJETS</a>
      <a class="nav_link" href="#contact">CONTACT</a>
      <a class="nav_link" href="../assets/pdf/CV-LAGRC.pdf" download="CV-LAGRC.pdf">Mon CV<img src="../assets/images/iconetelechargement.png" alt=""></a>
    </nav>

  </header>

</template>

<script setup>

</script>

<style scoped>

header {
  display: flex;
  justify-content: space-between;
  background: #ffffff99;
  padding: 18px 24px;
  position: sticky;
  box-shadow: 5px 5px 5px rgba(0,0,0,0.5);
  top: 0;
  left: 0;
  z-index: 1;
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

