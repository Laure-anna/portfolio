<template>

  <header>

    <a href="#"><img src="../assets/images/logo.png" alt="logo"></a>

    <div class="container_nav_bouton">
      <nav class="nav" ref="nav">
      <a class="nav_link" href="#apropos">A PROPOS</a>
      <a class="nav_link" href="#competences">COMPETENCES</a>
      <a class="nav_link" href="#projets">PROJETS</a>
      <a class="nav_link" href="#contact">CONTACT</a>
      <a class="nav_link" href="../../public/pdf/CV-LAGRC.pdf" target="_blank">Mon CV<img src="../assets/images/iconetelechargement.png" alt=""></a>
    </nav>

    <button class="button_burger" @click="toggleMenu">x</button>
    </div>

  </header>

</template>

<script setup>

import {ref} from "vue";

const isMenuVisible = ref(true);
const nav = ref(null);

const toggleMenu = () => {
  if(!isMenuVisible.value) {
    nav.value.style.display = "flex";
    isMenuVisible.value = true;
  } else {
    nav.value.style.display = "none";
    isMenuVisible.value = false;
  }
}

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
  background: rgba(255, 255, 255, 0.511);
  z-index: 10;
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

.container_nav_bouton {
  display: flex;
}

.button_burger {
  display: none;
 
}

@media screen and (width < 1024px) {
  .nav {
    flex-direction: column;
    position: absolute;
    padding: 16px;
    right: 0;
    top: 0;
    display: none;
  }

  .button_burger {
    display: block;
    z-index: 20;
  }
}



</style>

