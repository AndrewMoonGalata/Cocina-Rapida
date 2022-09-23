<template>
    <div class="card" style="width: 18rem;">
 
  <div class="card-body">
    <imagenes> <img v-bind:src="url" alt="..."></imagenes>
    <h5 class="card-title">{{nombre}}</h5>
    <p class="card-text">{{descripcion}}</p>

    <p class="card-text">Precio ${{costo}}</p>
    
  </div>
</div>
</template>

<script>
    import imagenes from "./Imagenes.vue"
    
        export default{
        props: {
            url: {
                String
            },
            nombre: {
                String
            },
            descripcion: {
                String
            },
            costo: {
                Number
            },
        },
        components:{
            imagenes
        }
        
    }

    </script>