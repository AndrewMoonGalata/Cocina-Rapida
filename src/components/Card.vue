<template>
    <div class="card" style="width: 18rem;">
  <img v-bind:src="url" class="card-img-top" alt="...">
  <div class="card-body">
    <h5 class="card-title">{{nombre}}</h5>
    <p class="card-text">{{descripcion}}</p>

    <p class="card-text">Precio ${{costo}}</p>
    
  </div>
</div>
</template>

<script>
    
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
        
    }
    </script>