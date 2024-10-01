<template>
  <aside>
    <div>
      <span>CEDULA DE INDENTIDAD</span>
      <img width="40" src="./assets/img/chile_bandera.png" alt="" />
    </div>

    <img src="./assets/img/foto_elon.jpg" alt="" />
    <p>RUN {{ run }}</p>
  </aside>

  <main>
    <header>
      <p>REPUBLICA DE CHILE</p>
      <span>SERVICIO DE REGISTRO CIVIL E IDENTIFICACIÓN</span>
    </header>
    <section>
      <article>
        <header>APELLIDOS</header>
        <span>{{ apellidos }}</span>
      </article>
      <article>
        <header>NOMBRES</header>
        <span>{{ nombres }}</span>
      </article>

      <div class="grid-2-colums">
        <article>
          <header>NACIONALIDAD</header>
          <span>{{ nacionalidad }}</span>
        </article>
        <article>
          <header>SEXO</header>
          <span>{{ sexo }}</span>
        </article>
      </div>
      <div class="grid-2-colums">
        <article>
          <header>FECHA DE NACIMIENTO</header>
          <span>{{ fechaNacimiento }}</span>
        </article>
        <article>
          <header>NÙMERO DOCUMENTO</header>
          <span>{{ numDoc }}</span>
        </article>
      </div>
      <div class="grid-2-colums">
        <article>
          <header>FECHA DE EMISIÒN</header>
          <span>{{ fechEmision }}</span>
        </article>
        <article>
          <header>FECHA DE VENCIMIENTO</header>
          <span>{{ fechVencimiento }}</span>
        </article>
      </div>
      <article>
        <header>FIRMA DEL TITULAR</header>
        <span>{{ firma }}</span>
      </article>
    </section>
  </main>
</template>

<script>
export default {
  name : 'App',
  data() {
    return {
      run: "22.222.222-2",
      apellidos: "MUSK",
      nombres: "ELON REEVE",
      nacionalidad: "SUDAFRICANO",
      sexo: "M",
      fechaNacimiento: "28 JUN 1971",
      numDoc: "222.222.222",
      fechEmision: "01 ENE 2025",
      fechVencimiento: "01 ENE 2030",
      firma: "X Æ A-12"
  }
}}
</script>

<style>
/* estilos en main.css */
</style>
