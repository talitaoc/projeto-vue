<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>{{titulo}}</h3>
    <p>
      Primeiro projeto em Vue<br>
      <a href="https://www.cieepr.org.br/" target="_blank" rel="noopener">Link Ciee</a>
    </p>
    <h3>Contato</h3>
    <ul>
      <li><a href="https://github.com/talitaoc" target="_blank" rel="noopener">Github</a></li>
      <li><a href="https://www.linkedin.com/in/talita-orlando-de-campos-2b6634146/" target="_blank" rel="noopener">Linkedln</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
    titulo: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 20px 0 0;
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
  color: #364ab9;
}
</style>
