<template>
    <div>
        <h1>Perros en adopcion</h1>
        <lista-mascotas/>
    </div>
</template>

<script>
  import ListaMascotas from '../components/ListaMascotas.vue'

  export default {
    name: 'app',
    components: {
      ListaMascotas,
    },
  }
</script>

