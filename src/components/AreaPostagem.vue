<script setup>
    import post from "./post.vue"
    import imagemysql           from '@/assets/imagemysql.jpg'
    import imgjavascript        from '@/assets/imgjavascript.jpg'
    import php                  from '@/assets/php.jpg'
</script>

<template>
    <div>
        <post :imagem="imagemysql" titulo="MySQL"
        texto="Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
  Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.
  Vestibulum ant..." />
  <br>
        <post :imagem="imgjavascript" titulo="Java Script" 
        texto="Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.
Vestibulum ant..."/>
<br>
        <post :imagem="php" titulo="PHP" 
        texto="Aqui haverá um texto Aqui haverá o texto 1. Lorem ipsum dolor sit amet, consectetur adipiscing elit.
Suspendisse euismod dignissim lectus in tempus. Phasellus quis porttitor leo.
Vestibulum ant..."/>
    </div>
</template>

<style scoped>
</style>