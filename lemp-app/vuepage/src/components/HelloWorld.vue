<template>
<div class="hero">
  <h1>¡Bienvenidos a Startup Politecnics ;)!</h1>
  <p>La plataforma que impulsa tus ideas al éxito.</p>
  <button class="btn">Explora Ahora</button>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
body, html {
    height: 100%;
    margin: 0;
    font-family: 'Arial', sans-serif;
  }
  .hero {
    background-color: #f06d06;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    flex-direction: column;
    text-align: center;
  }
  h1 {
    font-size: 50px;
    margin-bottom: 20px;
  }
  p {
    font-size: 20px;
    margin-bottom: 30px;
  }
  .btn {
    border: none;
    padding: 10px 20px;
    background-color: #fff;
    color: #f06d06;
    cursor: pointer;
    font-size: 18px;
    text-transform: uppercase;
    letter-spacing: 2px;
    transition: background-color 0.3s ease;
  }
  .btn:hover {
    background-color: #e5e5e5;
  }
</style>
