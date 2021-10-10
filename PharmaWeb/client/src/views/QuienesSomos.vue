<template>
<BasicLayouts>
<br>
<h1>Conoce nuestro equipo de trabajo</h1>
<h1>Team</h1>
<br>
<div class="ui link cards">
  <div class="card">
    <div class="image">
      <img src="../assets/team/SaraXimenaBastoHernandez.jpg">
    </div>
    <div class="content">
      <div class="header">Sara Ximena Basto Hernandez</div>
      <div class="meta">
        <a>Member team</a>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="image">
      <img src="../assets/logo.png">
    </div>
    <div class="content">
      <div class="header">Juan Pablo Martinez Aldana </div>
      <div class="meta">
        <a>Member team</a>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="image">
      <img src="../assets/team/FredAcostaEcheverria.jpg">
    </div>
    <div class="content">
      <div class="header">Fred Acosta Echeverria</div>
      <div class="meta">
        <a>Member team</a>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="image">
      <img src="../assets/team/DanielSantiagoCarreñoBriceño.jpg">
    </div>
    <div class="content">
      <div class="header">Daniel Santiago Carreño Briceño</div>
      <div class="meta">
        <a>Member team</a>
      </div>
    </div>
  </div>
  <div class="card">
    <div class="image">
      <img src="../assets/team/ChristianVanegasEchavarria.jpg">
    </div>
    <div class="content">
      <div class="header">Christian Vanegas Echavarría</div>
      <div class="meta">
        <a>Member team</a>
      </div>
    </div>
  </div>
</div>
</BasicLayouts>
</template>

<script>
import BasicLayouts from '../layouts/BasicLayouts.vue';

export default {
  name: "QuienesSomos",
  components: {
    BasicLayouts,
  },
};
</script>

<style>

h1{
  text-align: center;
  color:#3386FF ;
}

</style>
