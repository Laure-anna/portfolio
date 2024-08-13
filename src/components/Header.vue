<template>
  <header>
    <div class="logo">logo</div>
    <nav class="nav">
      <a class="nav_link" href="#">Lien 1</a>
      <a class="nav_link" href="#">Lien 2</a>
      <a class="nav_link" href="#">Lien 2</a>
    </nav>
  </header>
</template>

<script setup></script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  background: grey;
  padding: 18px 24px;
  position: sticky;
  box-shadow: 5px 5px 5px rgba(0,0,0,0.5);
}

.nav {
  display: flex;
  gap: 8px;
}

.nav_link {
  color: black;
  text-decoration: none;
}
</style>
