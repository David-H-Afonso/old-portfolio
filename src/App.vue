<template>
  <div id="app">
    <div class="projects">
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="../assets/img/diablo3.png"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="/img/batatabit.4a4b20ae.png"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="/img/python.6afbf459.png"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="/img/vue-store.cb8c59af.png"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="/img/vuedex.964aeba2.png"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
      <newProject 
        title="Diablo 3 Profile Viewer"
        img="https://repository-images.githubusercontent.com/383039158/62718c00-ddc0-11eb-81de-5ebd290c3cde"  
        desc="View any Diablo 3 Profile with the region and Battle Tag with this web app created with Vue and Stylus. By default, you can use SuperRambo#2613 in EU" 
        github_link="https://github.com/David-H-Afonso/diablo-3-profile-viewer" 
        link="https://diablo-3-profile-viewer.netlify.app/#/" />
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
