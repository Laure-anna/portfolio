<template>
  <h2>CONTACT</h2>

    <div class="liens_contacts">
        <a class="logo_gihub" href="https://github.com/Laure-anna" target="_blank"><img src="../assets/images/iconegithub.png" alt="logo github"></a>
        <a class="logo_mail" href="mailto:lagrc.dev@gmail.com" target="_blank"><img src="../assets/images/iconemail.png" alt="logo mail"></a>
        <a class="logo_telephone" href="tel:0668292281" target="_blank"><img src="../assets/images/iconetelephone.png" alt="logo github"></a>
    </div>

</template>

<script setup>

</script>

<style scoped>
    h2 {
    padding-right: 20px;
    padding-left: 20px;
    background: linear-gradient(transparent, white, transparent);
    font-family: "1942";
    text-align: center;
    font-size: 80px;
    color: #000000;
    font-weight: 300;
    margin-bottom: 100px;
    }

    img {
        width: 140px;
        background: rgba(252, 251, 251, 0.283);
        box-shadow: 10px 10px 10px rgba(96, 20, 20, 0.548);
    }

    .liens_contacts {
        display: flex;
        justify-content: space-around;
        padding-bottom: 100px;
    }
</style>