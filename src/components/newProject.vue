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
@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    *{
        font-family: 'Montserrat', sans-serif;
    }
    .project{
        display: flex;
        align-items: center;
        flex-direction: column;
        margin-bottom: 30px !important;
        margin: auto;
        width: 300px;
        height: 400px;
        overflow-x: hidden;
        background-color: #76C893;
        border: 1px solid #184E77;
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
        font-size: 24px;
    }
    p{
        text-align: center;
        color: #1A759F;
        font-size: 16px;
    }
    a{
       display: block;
       text-align: center;
       padding: 7px;
       margin: 5px;
       margin-top: -2px;
       border: 1px solid #184E77;
       text-decoration: none;
       color: whitesmoke;
       line-height: 20px;
       background-color: #1E6091;
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