<template>
    <h2>COMPETENCES</h2>
    <div class="liste_competences">
        
        <div id="competences" class="container_competences">
            <div class="competences">

                <div>
                    <img class="competences_images" src="../assets/images/pngwing.com.png" alt="logo HTML">
                    <h3 class="nom_competence">HTML</h3>
                </div>
                <div>
                    <img class="competences_images" src="../assets/images/javascript.png" alt="logo JavaScript">
                    <h3 class="nom_competence">JavaScript</h3>
                </div>
                <div>
                    <img class="competences_images" src="../assets/images/css.png"  alt="logo css">
                    <h3 class="nom_competence">CSS</h3>
                </div>
            </div>
        </div>
    </div>

</template>

<script setup>

</script>

<style scoped>

.liste_competences {
    display: flex;
    justify-content: space-around;
}

h2, h3 {
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

.container_competences {

    width: 95%;
    margin: auto;
    color: #fff;
}

.competences {
    display: flex;
    align-content: center;
    justify-content: space-around;
}

img {
    display: block;
    margin: auto;
    height: 200px;
    box-shadow: 5px 5px 5px 5px rgba(123, 7, 7, 0.516);
    border-radius: 20%;
}

.nom_competence {
    font-size: 30px;
    font-weight: 300;
    text-align: center;
    text-transform: capitalize;
    margin: 30px 0 20px;
}

</style>