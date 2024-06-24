<script>
export default{
  data(){
    return{
      licznik: 0
    }
  },
  methods:{
      increase(){
        this.licznik++
      }
  }

}
// import { ref } from 'vue';
</script>

<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <br />
    <br />
    <form action="#">
      <label for="name">Enter your name: &nbsp;</label>
      <input id="name" alt="Name" type="text" />
      <button type="submit">Click Me!</button>
    </form>
    <section id="greeting">Hello</section>
    <br/>
    <button @click="increase">Increase</button>
    {{ licznik }}
  </main>
</template>
