<template>
  <article class="hello">
    <img src="./../assets/jsserra.camisa.jpeg" alt="JSSerra Camisa">
    <h1>O QUE FAREMOS</h1>
    <h2> Tecnologia Web na Serra-ES </h2>
    <p>Comunidade criada e mantida com a finalidade de unir e conectar pessoas.</p>
    <p>Que gostam ou usam tecnologia para a web e que moram na Serra-ES.</p>
    <p>Se você é Dev ou entusiasta, ou até mesmo gosta do assunto é muito bem vindo!</p>
    <h2>Como</h2>
    <p>Vamos aprender, fazer acontecer, evoluir e falar sobre.</p>
    <p>Através de encontros, talks, palestras e aulas em locais físicos ou online.</p>
    <p>JUNTOS :D</p>
    <h2>Contato</h2>
    <p>Telegram <br> <a href="https://t.me/jsserra" target="_blank" rel="noopener">https://t.me/jsserra</a></p>
    <p>Meetup <br> <a href="https://www.meetup.com/pt-BR/jsserra/" target="_blank" rel="noopener">https://www.meetup.com/pt-BR/jsserra/</a></p>
    <p>Seja bem vindo ao clube <strong>JSSERRA</strong>!</p>
  </article>
</template>

<script>
export default {
  name: 'JsSerraBanner',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  object-fit: cover;
  object-position: 0px -40px;
  width: 800px;
  height: 250px;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.hello {
  max-width: 800px;
  margin: auto;
  background-color: white;
  padding-bottom: 50px;
}
.hello p{
  padding-left: 20px;
  padding-right: 20px;
}
.hello h1{
  padding-left: 20px;
  padding-right: 20px;
}
.hello h2{
  padding-left: 20px;
  padding-right: 20px;
}
</style>
