<script>
// import AppHero from './AppHero.vue';
export default {
  data(){
    return{
      title:'La mia prima app con Vite!',
    }
  },
  methods: {
    haicliccato() {
      console.log('hai cliccato')
    }
  },
  components: {
    // AppHero
  }
}
</script>

<template>
  <div>
    <h1>{{title}}</h1>
  </div>
  <button @click="haicliccato()">Clicca  qui!</button>

  
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
