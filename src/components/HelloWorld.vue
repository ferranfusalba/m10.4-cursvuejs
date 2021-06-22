<template>
  <div class="hello">
    <br>
    <h1>Exercici d'instal·lació de l'entorn VueJS</h1>
    <br>
    <h2>NodeJS, VueJS, Plugins, SASS, Bootstrap</h2>
    <br>
    <p><b>Instal·lat segons el mostrat al mòdul M10.4 (ordre aproximat)</b></p>
    <p>Instal·lació node i comprovació última versió via node --version</p>
    <p>Instal·lació extensió Chrome <i>Vue.js devtools</i> i extensió VSCode <i>Vetur</i></p>
    <p>vue create cursvuejs (Sass/SCSS (with dart-sass))</p>
    <p>npm install vuelidate --save + config. manual a main.js</p>
    <p>npm install vue-router + comprovació registre a package.json</p>
    <p>npm install vuex --save + creació store.js + config. manual a main.js</p>
    <p>npm install axios</p>
    <p>Integració SASS (creació Carpeta <i>Style > CSS / SCSS</i> i link de <i>HelloWorld.vue</i> a <i>HelloWorld.scss</i>)</p>
    <p>npm install vue bootstrap bootstrap-vue + config. manual a main.js</p>
    <p>Separar Arxius App.vue (Style a SCSS i CSS i Scripts a App.js)</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style src="../Styles/HelloWorld.scss" lang="scss" scoped>

</style>
