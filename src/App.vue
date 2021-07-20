<template>
  <div id="app">
    <div class="projects">
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="https://repository-images.githubusercontent.com/383039158/62718c00-ddc0-11eb-81de-5ebd290c3cde"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Batatabit Crypto Coin Web"
        img="https://repository-images.githubusercontent.com/356080858/d44ad500-ddc2-11eb-89e7-84cb9c8ed1d5"  
        desc="Static HTML and CSS page without using any preprocessor or framework, to try my cappacities doing a responsive web design." 
        github_link="https://github.com/David-H-Afonso/batatabit-html-css-learning-page" 
        link="https://batatabit-html-css-learning-page.netlify.app/" />
      <newProject 
        title="Vuedex! A Vue.js Pokedex"
        img="https://repository-images.githubusercontent.com/380185759/fc7f0780-ddb3-11eb-8866-243097bd0e1b"  
        desc="Web app developed consuming PokeApi where you can see randomly a Pokémon sprite, ability, stats and main type." 
        github_link="https://github.com/David-H-Afonso/vuedex" 
        link="https://vuedex-dha.netlify.app/" />
      <newProject 
        title="Vue.js E-commerce Template"
        img="https://repository-images.githubusercontent.com/371701259/86cf6780-ddc4-11eb-85e5-c02d564b7380"  
        desc="Web app where I've created the basis of an e-commerce online shop, creating discount codes, a cart, products, using specific size for pictures, etc. Really useful as a base and so good for learning" 
        github_link="https://github.com/David-H-Afonso/vue-js-store-template" 
        link="https://vue-js-store-template.netlify.app/" />
      <newProject 
        title="Python Learning tests"
        img="https://repository-images.githubusercontent.com/384547425/30cf2c80-e102-11eb-9abf-d0c97088836c"  
        desc="I've created 4 projects on Python to practise my knowledge. A password generator, coin exchange, 'Is it Prime?' program and 'Guess the number' mini game" 
        github_link="https://github.com/David-H-Afonso/python-basic-tests" />
      <newProject 
        title="Portfolio"
        img=""  
        desc="WIP" 
        github_link="https://github.com/David-H-Afonso/portfolio" 
        link="https://portfolio-david-h-afonso.netlify.app/" />
    </div>
  </div>
</template>

<script>
import newProject from "./components/newProject.vue";

export default {
  name: "App",
  components: {
    newProject,
  },
};
</script>

<style>
#app {
  margin: 0px auto;
  padding: 0px;
}
.projects{
  display: flex;
  flex-wrap: wrap;
}
</style>
