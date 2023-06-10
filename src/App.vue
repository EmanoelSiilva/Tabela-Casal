<template>
  <div class="container">
    <h1>Dentro dessa div há um espaçamento de 20px entre os elementos P</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti delectus ea expedita cum sequi accusantium, praesentium eum explicabo amet quos sit eveniet libero error provident porro dignissimos facilis hic quidem.</p>
    <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ex excepturi quas quo? Eligendi veniam accusamus perferendis! Repellendus voluptas deleniti ut explicabo quidem distinctio qui provident placeat nulla quia, sequi alias?</p>
  </div>


  <table>
    <tr>
      <th>Nome</th>
      <th>Idade</th>
    </tr>

    <tr>
      <td>João</td>
      <td>25</td>
    </tr>
  </table>

  <div>
    <button @click="handleClick()" >Play</button>
  </div>

      
</template>

<script>

export default {
  name: 'App',
  data() {

  },
  methods: {
    handleClick() {
      alert('Foi clicado')
    }
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  align-items: center;
}

.container, p {
  margin-top: 20px;
}


table, th, td {
  border: 1px solid black;
}

table {
  border-collapse: collapse;
  margin: auto;
}

th, td {
  padding: 10px;
  text-align: center;
  width: 120px;
}

button {
  background-color: #00f;
  color: #ffffff;
  border-radius: 10px;
  padding: 10px;
  margin: 100px;
}
</style>
