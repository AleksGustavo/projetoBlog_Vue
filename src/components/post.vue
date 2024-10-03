<script>
    export default{
        name:'post',
        props: {
            imagem:{
                type: String,
                required:false
            },
            titulo: {
                type: String,
                required:true
            },
            texto: {
                type: String,
                required:true
            },
            autor: {
                type: String,
                required:false
            }
        }
    }
</script>

<template>
  <div id="container">
      <img v-if="imagem" :src="imagem" alt="sem imagem">

      
        <h2>{{ titulo }}</h2>
        <p>{{ texto }}</p>
        <p>{{ autor }}</p>
  </div>
</template>

<style scoped>
#container{
    position: relative;
    background-color: rgb(187, 181, 181);
    width: 1000px;
    height: 700px;
    
}

#container img{
    margin: 25px 75px;
    position: relative;
    width: 900px;
    height: 500px;
}

#container h1{
    position: relative ;
    
    left: 110px;
    color: black;       
}

#container :nth-child(2){
    font-size: 20px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;
}

#container :nth-child(3){
    font-size: 20px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;
}

#container :nth-child(5){
    font-size: 25px;
    color: black;
    display: flex;
    text-align: justify;
    margin-left: 50px;
    margin-right: 10px;
}
</style>