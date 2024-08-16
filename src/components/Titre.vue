<template>

  <p class="ligne animation">BIENVENUE SUR MON SITE WEB</p>
  
</template>

<script setup>

</script>

<style scoped>
    
p {
    font-family: '1942';
    text-shadow: 5px 5px 5px rgba(232, 227, 227, 0.842);
    color: rgb(82, 12, 12);
    font-weight: 800;
    padding-right: 50px;
    
}

.ligne {
      position: relative;
      top: 50%;
      width: 16em;
      margin-top: 250px;
      margin-bottom: 250px;
      margin-left: 20%;
      border-right: 2px solid rgba(17, 7, 7, 0.75);
      font-size: 300%;
      text-align: center;
      white-space: nowrap;
      overflow: hidden;transform: translateY(-50%);
}


.animation {
      animation: typewriter 4s steps(40) 1s 1 normal both,
      blinkTextCursor 500ms steps(40) infinite normal;
}

@keyframes typewriter {
      from {
            width: 0;
      }
      to {
            width: 16em;
      }
}

@keyframes blinkTextCursor {
      from {
            border-right-color: rgba(235, 226, 226, 0.75);
      }
      to {
            border-right-color: transparent;
      }
}

</style>

