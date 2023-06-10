<template>
    <div id="container">
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

      <button>Play</button>
  </div>
</template>

<script>

export default {
  name: 'App'
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
