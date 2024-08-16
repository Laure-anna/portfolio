<template>

  <h2>PROJETS</h2>

  <ul id="projets" class="cartes">
    <li class="axe_cartes">
      <figure class="face_cartes">
        <img src="../assets/images/portfolioscreen.png" alt="image portfolio"/>
        <figcaption class="titre_cartes">
          <p>Portfolio</p>
        </figcaption>
      </figure>

      <figure class="dos_cartes">
        <img src="../assets/images/portfolioscreen.png" alt="image portfolio"/>
        <figcaption class="description_cartes">
          <p>Portfolio en HTML, CSS et JavaScript</p>
        </figcaption>
      </figure>
    </li>

    <li class="axe_cartes">
      <figure class="face_cartes">
        <img src="../assets/images/askalyascreen.png" alt="image askalya"/>
        <figcaption class="titre_cartes">
          <p>ASKALYA</p>
        </figcaption>
      </figure>

      <figure class="dos_cartes">
        <img src="../assets/images/askalyascreen.png" alt="image askalya"/>
        <figcaption class="description_cartes">
          <p>Site en HTML et CSS</p>
        </figcaption>
      </figure>
    </li>

    <li class="axe_cartes">
      <figure class="face_cartes">
        <img src="../assets/images/chargementscreen.png" alt="image chargement"/>
        <figcaption class="titre_cartes">
          <p>Prochainement</p>
        </figcaption>
      </figure>

      <figure class="dos_cartes">
        <img src="../assets/images/chargementscreen.png" alt="image chargement"/>
        <figcaption class="description_cartes">
          <p>...</p>
        </figcaption>
      </figure>
    </li>

    <li class="axe_cartes">
      <figure class="face_cartes">
        <img src="../assets/images/chargementscreen.png" alt="image chargement"/>
        <figcaption class="titre_cartes">
          <p>Prochainement</p>
        </figcaption>
      </figure>

      <figure class="dos_cartes">
        <img src="../assets/images/chargementscreen.png" alt="image chargement"/>
        <figcaption class="description_cartes">
          <p>...</p>
        </figcaption>
      </figure>
    </li>
  </ul>

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
  text-transform: capitalize;
  font-weight: 300;
  margin-bottom: 100px; 
    
}

*, *:before, *:after { 
  -moz-box-sizing: border-box; 
  -webkit-box-sizing: border-box; 
  box-sizing: border-box; 
}

body { 
  background: #333; 
  font-family: 'Georgia', sans-serif; 
}

h1 {  
  position: absolute; 
  top: 150px; 
  left: -115px; 
  font-size: 1.25em; 
  color: #fff; 
  -webkit-transform: rotate(-90deg); 
  -moz-transform: rotate(-90deg); 
  -ms-transform: rotate(-90deg); 
  -o-transform: rotate(-90deg); 
  transform: rotate(-90deg);}

.cartes * {
  width: 100%;
}

.axe_cartes {
	position: relative;
}

.axe_cartes:before {
	content: "";
	display: block;
	padding-top: 100%;
}

.face_cartes, .dos_cartes {
	position: absolute;
	top: 0;
  margin: 0;
	-webkit-transition: 0.5s ease-in-out;
	-moz-transition: 0.5s ease-in-out;
	-ms-transition: 0.5s ease-in-out;
	-o-transition: 0.5s ease-in-out;
	transition: 0.5s ease-in-out;
  box-shadow: 5px 5px 5px 5px rgba(123, 7, 7, 0.516);
}

.face_cartes {
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	-ms-backface-visibility: hidden;
	-o-backface-visibility: hidden;
	backface-visibility: hidden;
  
	-webkit-transform: perspective(1000px) rotateY(0deg);
	-moz-transform: perspective(1000px) rotateY(0deg);
	-ms-transform: perspective(1000px) rotateY(0deg);
	-o-transform: perspective(1000px) rotateY(0deg);
	transform: perspective(1000px) rotateY(0deg);
}

.axe_cartes:hover .face_cartes {
	-webkit-transform: perspective(1000px) rotateY(-180deg);
	-moz-transform: perspective(1000px) rotateY(-180deg);
	-ms-transform: perspective(1000px) rotateY(-180deg);
  -o-transform: perspective(1000px) rotateY(-180deg);
	transform: perspective(1000px) rotateY(-180deg);
}

.dos_cartes {
	-webkit-backface-visibility: hidden;
	-moz-backface-visibility: hidden;
	-ms-backface-visibility: hidden;
	-o-backface-visibility: hidden;
	backface-visibility: hidden;
  
	-webkit-transform: perspective(1000px) rotateY(180deg);
	-moz-transform: perspective(1000px) rotateY(180deg);
	-ms-transform: perspective(1000px) rotateY(180deg);
	-o-transform: perspective(1000px) rotateY(180deg);
	transform: perspective(1000px) rotateY(180deg);
}

.axe_cartes:hover .dos_cartes {
	-webkit-transform: perspective(1000px) rotateY(0);
	-moz-transform: perspective(1000px) rotateY(0);
	-ms-transform: perspective(1000px) rotateY(0);
	-o-transform: perspective(1000px) rotateY(0);
	transform: perspective(1000px) rotateY(0);
}

.cartes {
  width: 80%;
  margin: 0 10%;
  list-style-type: none;
  padding-left: none;
}

.cartes:after {
	content: "";
	display: table;
	clear: both;
}

.axe_cartes {
  float: left;
  margin-left: 2.5%;
	width: 20%;
}

.axe_cartes img {
  border: 15px solid #fff;
  border-bottom-width: 45px;
}

.titre_cartes {
  position: absolute;
  bottom: -10px;
  width: 100%;
  text-align: center;
  font-size: 1.5em;
}

.description_cartes {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 90%;
  background: rgb(255,255,255);
  background: rgba(255,255,255,0.9);
}

.description_cartes p {
  position: absolute;
  width: 100%;
  top: 50%;
  margin-top: -1em;
  text-align: center;
  font-size: 15px;
  color: #000000;
}
</style>