<template>
  <footer>
      <div class="container contact">
        <p>Dirección<br>Calle X #123<br>Colonia Estado de México</p>
        <p>Teléfono<br>5512345678</p>
        <p>Horarios<br>10:00 a 20:00 hrs</p>
      </div>
    </footer>
</template>

<script>
export default {
  name: 'ContactFooter',
}
</script>

<style scoped>
  footer {
    margin-top: 3vh;
    background-color: var(--moradoKittsu);
    height: 100px;
    width: 100%;
  }
  footer p {
    color: white;
    font-family: 'Ubuntu Condensed', sans-serif;
    font-size: 1.1em;
    padding: 1em;
    text-align: left;
  }
  .contact {
    align-items: flex-start;
    display: flex;
    justify-content: flex-start;
  }
</style>