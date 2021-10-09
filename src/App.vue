<template>
  <div id="app">
    <header>
      <a href="#aboutmelink">About me</a>
      <a href="#projects">Projects</a>
      <a href="#contactme">Contact</a>
    </header>
    <div id="presentation">
      <img
        src="./assets/profile-pic.png"
        alt="david hormiga afonso picture"
      />
      <h1>David Hormiga Afonso</h1>
      <h2>Frontend web Developer</h2>
    </div>
    <div id="aboutmelink"><br /></div>
    <div id="aboutme">
      <h2>About me</h2>
      <p>
        Organized, proactive and always learning, I am a person with a great
        passion for web development. Currently focused on the front-end with
        Vue.js. <br />
        Since I was 15 I have been interested in the entire world of web
        development. At 16 I began to investigate intensively and at 17 I
        dedicated myself to studying on my own, thanks to Platzi and several
        online courses prior to this school to learn about this sector and
        acquire the necessary knowledge to work in this industry. <br />
        I have worked with technologies like HTML5, CSS3, JavaScript, Git and
        GitHub, Vue, npm...
      </p>
    </div>
    <center><h2 class="title">Projects</h2></center>
    <div id="projects">
      <!-- Diablo 3 Profile Viewer -->
      <newProject
        title="Diablo 3 Profile Viewer"
        img="https://repository-images.githubusercontent.com/383039158/62718c00-ddc0-11eb-81de-5ebd290c3cde"
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU"
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer"
        link="https://diablo-3-profile-viewer.netlify.app/#/"
      />
      <!-- Batatabit Crypto Coin Web -->
      <newProject
        title="Batatabit Crypto Coin Web"
        img="https://repository-images.githubusercontent.com/356080858/d44ad500-ddc2-11eb-89e7-84cb9c8ed1d5"
        desc="Static HTML and CSS page without using any preprocessor or framework, to try my cappacities doing a responsive web design."
        github_link="https://github.com/David-H-Afonso/batatabit-html-css-learning-page"
        link="https://batatabit-html-css-learning-page.netlify.app/"
      />
      <!-- Vuedex! A Vue.js Pokedex -->
      <newProject
        title="Vuedex! A Vue.js Pokedex"
        img="https://repository-images.githubusercontent.com/380185759/fc7f0780-ddb3-11eb-8866-243097bd0e1b"
        desc="Web app developed consuming PokeApi where you can see randomly a Pokémon sprite, ability, stats and main type."
        github_link="https://github.com/David-H-Afonso/vuedex"
        link="https://vuedex-dha.netlify.app/"
      />
      <!-- Vue.js E-commerce Template -->
      <newProject
        title="Vue.js E-commerce Template"
        img="https://repository-images.githubusercontent.com/371701259/86cf6780-ddc4-11eb-85e5-c02d564b7380"
        desc="Web app where I've created the basis of an e-commerce online shop, creating discount codes, a cart, products, using specific size for pictures, etc. Really useful as a base and so good for learning"
        github_link="https://github.com/David-H-Afonso/vue-js-store-template"
        link="https://vue-js-store-template.netlify.app/"
      />
      <!-- Python Learning tests -->
      <newProject
        title="Python Learning tests"
        img="https://repository-images.githubusercontent.com/384547425/30cf2c80-e102-11eb-9abf-d0c97088836c"
        desc="I've created 4 projects on Python to practise my knowledge. A password generator, coin exchange, 'Is it Prime?' program and 'Guess the number' mini game"
        github_link="https://github.com/David-H-Afonso/python-basic-tests"
      />
      <!-- Portfolio -->
      <newProject
        title="Portfolio"
        img="https://repository-images.githubusercontent.com/384706007/38e7ff92-bc00-4533-8300-cf7c93b896e0"
        desc="My portfolio with all my projects to show in a more visual way. Inside you have an about me section, contact section and project section with github links and deploy links"
        github_link="https://github.com/David-H-Afonso/portfolio"
        link="https://portfolio-david-h-afonso.netlify.app/"
      />
       <!-- React shopping cart -->
      <newProject
        title="Shopping Cart - React ⚠Work In Progress🚧"
        img="https://repository-images.githubusercontent.com/410687291/56ef53d4-21d3-4985-ab97-bd23d5a6f990"
        desc="React add to cart project WIP"
        github_link="https://github.com/David-H-Afonso/react-add-to-cart"
        link="https://shopping-cart-react-dha.netlify.app/"
      />
       <!-- React user manager -->
      <newProject
        title="User Manager - React ⚠Work In Progress🚧"
        img="https://repository-images.githubusercontent.com/412541187/8bd9cafe-434e-4d5f-a0b9-066e82b28ef9"
        desc="React user manager WIP"
        github_link="https://github.com/David-H-Afonso/user-manager"
        link="https://user-manager-react-dha.netlify.app/"
      />
      <!-- React image searcher -->
      <newProject
        title="Image searcher - React ⚠Work In Progress🚧"
        img="https://repository-images.githubusercontent.com/414614250/5bfa62e2-2859-4f48-98c6-1d52c64c38ac"
        desc="React image searcher WIP"
        github_link="https://github.com/David-H-Afonso/image-searcher"
        link="https://image-searcher-react-dha.netlify.app/"
      />
      <!-- React interes compuesto -->
      <newProject
        title="Calculadora de interés compuesto - React ⚠Work In Progress🚧"
        img="https://repository-images.githubusercontent.com/415404902/e6378d14-a3a4-42f3-a3d9-f070dd732eb3"
        desc="Calculadora de interés compuesto en React WIP"
        github_link="https://github.com/David-H-Afonso/interes-compuesto"
        link="https://interes-compuesto-react-dha.netlify.app/"
      />
    </div>
    <center><h2 class="title">Contact me</h2></center>
    <div id="contactme">
      <div>
        <img src="./assets/linkedin.png" alt="" /> <br>
        <a target="_blank" href="https://www.linkedin.com/in/david-hormiga-afonso">LinkedIn</a>
      </div>
      <div>
        <img src="./assets/github.png" alt="" /> <br>
        <a target="_blank" href="https://github.com/David-H-Afonso">GitHub</a>
      </div>
      <div>
        <img src="./assets/gmail.png" alt="" /> <br>
        <a target="_blank" href="mailto:davidhormigafonso@gmail.com?Subject=Quiero%20contactar%20contigo">Gmail</a>
      </div>
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
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap");
* {
  margin: 0px auto;
  padding: 0px;
  font-family: "Montserrat", sans-serif;
}
header {
  display: flex;
  height: 60px;
  width: 100%;
  margin-bottom: 50px;
  background-color: #808080be;
}
header a {
  color: #f1f1f1;
  text-decoration: none;
  line-height: 60px;
  font-size: 18px;
  transition: all 300ms;
}
header a:hover {
  color: #82b7dc;
}
.title {
  color: #114084;
  font-size: 2em;
  margin-bottom: 60px;
}
#projects {
  display: flex;
  flex-wrap: wrap;
}
#presentation {
  display: flex;
  flex-flow: column;
  align-items: center;
  margin-bottom: 250px;
  text-align: center;
}
#presentation h1 {
  margin-top: 10px;
  margin-bottom: 15px;
  color: #114084;
}
#presentation h2 {
  color: #3466aa;
}
#presentation img {
  width: 300px;
  border-radius: 300px;
}
#aboutme {
  display: flex;
  flex-flow: column;
  align-items: center;
  text-align: center;
  line-height: 25px;
  width: 90%;
}
#aboutme h2 {
  color: #114084;
  margin-bottom: 15px;
}
#aboutme p {
  color: #3466aa;
  margin-bottom: 205px;
}
#contactme {
  display: flex;
  align-items: center;
  text-align: center;
  margin-bottom: 30px;
}
#contactme a{
  text-decoration: none;
  margin-top: 10px;
  color: #114084 ;
}
#contactme img {
  width: 100px;
}
</style>
