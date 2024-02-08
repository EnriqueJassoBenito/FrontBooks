<template>
  <div>
    <div class="color-1">
      <h1 class="texto">Bibloteca</h1>
    </div>

    <!-- Boton para agregar libros -->
    <div class="btn-post">
      <b-button v-b-modal.modal-1 variant="success">Agregar</b-button>

      <b-modal id="modal-1" title="BootstrapVue">
        <p class="my-4">Hello from modal!</p>
      </b-modal>
    </div>

    <!-- Cards para agregar libros -->
    <div>
      <b-card
        title="El llano en llamas"
        img-src="https://picsum.photos/600/300/?image=25"
        img-alt="Image"
        img-top
        tag="article"
        style="max-width: 20rem"
        class="mb-2"
      >

        <b-card-text>
            Juan Rulfo
        </b-card-text>
        <b-card-text>
            El llano en llamas​ libro de cuentos del escritor mexicano Juan Rulfo, publicado el 1 de septiembre de 1953 bajo 
            la editorial Fondo de Cultura Económica. Fue la primera publicación del escritor, si bien ciertos relatos habían 
            sido publicados anteriormente en la revista América, en 1950.​
        </b-card-text>

        <b-card-text>
            Editorial
        </b-card-text>

        <b-card-text>
            anio
        </b-card-text>

        <b-card-text>
            genero
        </b-card-text>
      </b-card>
    </div>

  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.color-1 {
  background-color: lightblue;
}
.texto {
  text-align: center;
}
.btn-post {
  align-self: self-end;
}
</style>