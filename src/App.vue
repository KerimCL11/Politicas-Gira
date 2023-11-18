<template>
  <div id="app">
    <div id="politica-de-privacidad">
      <h1>Gira Gira</h1>

      <h2>Política de Privacidad</h2>
      <p>Bienvenido a nuestra aplicación. Esta aplicación no recopila ni utiliza información personal de los usuarios.</p>

      <h3>Información recopilada</h3>
      <p>Nuestra aplicación no recopila ningún tipo de información personal del usuario. No almacenamos datos, no accedemos a la cámara ni al micrófono, y no utilizamos ninguna funcionalidad que requiera el acceso a información sensible.</p>

      <h3>Uso de la información</h3>
      <p>Como no recopilamos información personal, no utilizamos ni compartimos ninguna información con terceros. La aplicación está diseñada para ser simple y no tiene funciones que requieran el uso de datos del usuario.</p>

      <h3>Privacidad del usuario</h3>
      <p>La privacidad del usuario es nuestra prioridad. No rastreamos ni almacenamos ninguna información que pueda identificar a los usuarios. La aplicación se centra en proporcionar una experiencia de usuario sencilla y divertida.</p>

      <h3>Contacto</h3>
      <p>Si tienes alguna pregunta sobre nuestra política de privacidad, no dudes en contactarnos en juanpivl@hotmail.com.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {},
};
</script>

<style>
#app {
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh; /* Ocupa toda la altura de la ventana */
}

#politica-de-privacidad {
  max-width: 600px; /* Ajusta según el diseño deseado */
  text-align: justify;
}
</style>
