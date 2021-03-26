<template>
  <div class="home">
    <img alt="Logo Airvault" src="../assets/logo.png">
    <h1>Airvault</h1>
    <p>Générateur de mots de passe</p>
    <form action="#">
      <input type="text" name="user_input" id="user_input">
      <button type="submit">Générer 2 mots de passe</button>
    </form>
  </div>
</template>

<script>
export default {
  name: 'Home',
}
</script>

<style lang="scss" scoped>
.home {
  padding:3rem 0;

  form {
    margin:2rem 0;

    input, button {
      display:block;
      width:300px;
      margin:0 auto;
      border:none;
      border-radius:4px;
    }

    input {
      border:1px solid #ddd;
      padding:0.5rem 0;
      margin-bottom:1rem;

      &:focus {
        border: none;
        box-shadow: 0 0 0 0.2rem hsla(347, 100%, 65%, 0.5);
        outline:1px solid hsla(347, 100%, 65%, 0.5);
      }
    }

    button {
      background-color:hsl(347, 100%, 65%);
      padding:0.5rem 0;
      color:#fff;
      font-weight:bold;

    }
  }
}


</style>
