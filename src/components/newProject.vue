<template>
  <div class="project">
    <center><img :src="img"></center>
    <h2>{{ title }}</h2>
    <p>{{desc}}</p>
    <div class="links">
       <a target="_blank" :href="github_link">GitHub Link</a>
       <a target="_blank" :href="link" v-if="link">Deploy Link</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "newProject",
  props: {
    title: String,
    img: String,
    desc: String,
    github_link: String,
    link: String,
  },
  data() {
    return {};
  },
};
</script>

<style scoped>
    .project{
        display: flex;
        align-items: center;
        flex-direction: column;
        margin-bottom: 30px !important;
        margin: auto;
        width: 300px;
        height: 400px;
        overflow-x: hidden;
        background-color: #F1F1F1;
        border: 1px solid #3466AA;
        border-radius: 35px;
    }
    .links{
        display: flex;
        flex-wrap: wrap;
    }
    img{
        width: 300px;
        height: 200px;
    }
    h2{
        margin-top: 4px;
        margin-bottom: -10px;
        text-align: center;
        color: #184E77;
        font-size: 20px;
    }
    p{
        text-align: center;
        color: #3466AA;
        font-size: 14px;
        margin-top: 10px;
        margin-bottom: 15px;
    }
    a{
       display: block;
       text-align: center;
       padding: 7px;
       margin: 5px;
       margin-top: -2px;
       border: 1px solid #114084;
       text-decoration: none;
       color: #F1F1F1;
       line-height: 20px;
       background-color: #114084;
       border-radius: 35px; 
    }
    @media (min-width: 1024px) {
    .project {
        width: 600px;
        height: 600px;
    }
    img{
        width: 600px;
        height: 340px;
    }
    h2{
        width: 95%;
        margin-top: 14px;
        margin-bottom: 2px;
        font-size: 30px;
    }
    p{
        width: 95%;
        font-size: 17px;
    }
    .links{
        margin-top: 19px;
    }
    a{
        margin-top: 50px;
        margin: 18px;
        padding: 10px;
    }
}
</style>