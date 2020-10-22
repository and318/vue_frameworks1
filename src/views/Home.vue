<template>
  <b-container>
   <b-row class="mt-5">
    <b-col cols="4" v-for="hero in superhero" :key="superhero.nombre">
        <b-card
    :title="hero.nombre"
    :img-src="hero.imagen"
    img-alt="ts"
    img-top
    tag="article"
    style="max-width: 20rem;"
    class="mb-2"
  >
   
  </b-card>
    </b-col>
    <b-col>2 of 2</b-col>
  </b-row>

</b-container>
</template>

<script>
export default {
    name: 'component-grid',
    // props: {},
    data () {
        return{
            superhero:[
            {
            id: 1, 
            nombre:'Batman',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/639.jpg'
            },
            {
            id: 2, 
            nombre:'Superman',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/791.jpg'
            },
              {
            id: 3, 
            nombre:'Wonder Woman',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/807.jpg'
            },
              {
            id: 4, 
            nombre:'Flash',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/892.jpg'
            },
              {
            id: 5, 
            nombre:'Aquaman',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/634.jpg'
            },
              {
            id: 6, 
            nombre:'Green Lantern',
            imagen:'https://www.superherodb.com/pictures2/portraits/10/100/697.jpg'
            },
        ]   
        }
    },
    // computed: {},
    methods: {
        // -- Metodos
    },
    // components: {},
}
</script>
