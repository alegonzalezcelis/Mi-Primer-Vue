<template>
  <div id="app">
    <div class="container">
      <h1 id="titulo">Tabla de usuarios</h1>
      <table class="table">
        <thead>
          <tr>
            <th scope="col">#</th>
            <th scope="col">Nombre</th>
            <th scope="col">Apellido</th>
            <th scope="col">Run</th>
            <th scope="col">Fecha de Nacimiento</th>
            <th scope="col">Edad</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <th scope="row">1</th>
            <td>{{usuario1.nombre}}</td>
            <td>{{usuario1.apellido}}</td>
            <td>{{usuario1.run}}</td>
            <td>{{usuario1.nacimiento}}</td>
            <td>{{usuario1.edad}}</td>
          </tr>
          <tr>
            <th scope="row">2</th>
            <td>{{usuario2.nombre}}</td>
            <td>{{usuario2.apellido}}</td>
            <td>{{usuario2.run}}</td>
            <td>{{usuario2.nacimiento}}</td>
            <td>{{usuario2.edad}}</td>
          </tr>
          <tr>
            <th scope="row">3</th>
            <td>{{usuario3.nombre}}</td>
            <td>{{usuario3.apellido}}</td>
            <td>{{usuario3.run}}</td>
            <td>{{usuario3.nacimiento}}</td>
            <td>{{usuario3.edad}}</td>
          </tr>
        </tbody>
</table>
    </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  data : () => ({
    usuario1: {
      nombre: "Jose",
      apellido: "Pérez",
      run: "123456-2",
      nacimiento: "12-04-57",
      edad: 52
    },
    usuario2: {
      nombre: "María",
      apellido: "Rodríguez",
      run: "654321-1",
      nacimiento: "30-11-90",
      edad: 29
    },
    usuario3: {
      nombre: "Manuel",
      apellido: "Patiño",
      run: "14223456-6",
      nacimiento: "02-12-59",
      edad: 60
    }
  })
}
</script>

<style>
  #titulo {
    text-align: center;
    margin: 10px 0 20px 0;
  }
</style>
