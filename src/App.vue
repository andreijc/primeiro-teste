
<template>
  <div>
    <NavBar />
    <RouterView />
  </div>
</template>
<script>
import NavBar from './components/navBar.vue';


export default {
  components: {
    NavBar
  }
}
</script>
<style>
:root {
  --cor1: #5CEB1A;
  --cor2: #1AEB72;
  --cor3: #1AEA2B;
  --cor4: #B3EB1A;
  --cor5: #1AEBB9;

  --font-basica: Arial, Helvetica, sans-serif;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;

  font-family: var(--font-basica);
}

a {
  text-decoration: none;
}

body {
  background-color: var(--cor2);
}

main {
  background-color: white;
  max-width: 800px;
  margin: auto;

  padding: 9px;
}

h1 {
  color: var(--cor2);
  text-shadow: 1px 1px 1px black;
}

p {
  margin: 15px;
  line-height: 1.5em;
}

</style>
