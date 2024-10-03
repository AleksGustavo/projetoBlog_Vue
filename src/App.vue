<script>
import AreaPostagem from "./components/AreaPostagem.vue"
import cabecalho from './components/cabecalho.vue'

export default{
        name:'App',
        components: { 
            cabecalho, 
            AreaPostagem
    },
    data() {
        return {

        }; 
    }
  }
</script>

<template>
    <div>
        <div>
          <cabecalho/>
        </div>   
        <div>
          <AreaPostagem/>
        </div>
    </div> 
</template>

<style scoped>
</style>
