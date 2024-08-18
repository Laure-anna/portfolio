<template>

  <section>
    <div id="apropos" class="presentation">
        <p>A 27 ans, je suis en reconversion dans le développement web.
            Passionnée par le potentiel infini du monde digital, je me consacre 
            à acquérir les compétences nécessaires pour réussir dans cette industrie 
            en constante évolution.</p>
    </div>
    
    <div class="photola">
        <img src="../assets/images/photola.png" alt="photo">
    </div>
  </section>

</template>

<script setup>

</script>

<style scoped>

  section {
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  @keyframes float {
    0% {
      box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
      transform: translatey(0px);
    }
    50% {
      box-shadow: 0 25px 15px 0px rgba(0,0,0,0.2);
      transform: translatey(-20px);
    }
    100% {
      box-shadow: 0 5px 15px 0px rgba(0,0,0,0.6);
      transform: translatey(0px);
    }
  }

  img {
    width: 300px;
    animation: float 6s ease-in-out infinite;
  }

  div {
    margin-top: -30px;
    padding: 40px;
  }  

  .presentation {
    background: #ffffff99;
    margin-left: 50px;
    margin-right: 50px;
    box-shadow: 5px 5px 5px 5px rgba(123, 7, 7, 0.516);
    border-radius: 1%;
  }

  p {
    font-family: 'AVELIRE';
    font-weight: 900;
    word-spacing: 5px;
    letter-spacing: 2px;
    line-height: 40px;
    font-size: 30px;
  }
  
</style>


