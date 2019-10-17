<template>
  <div class="hello">

    <h1>Welcome to the Movie App</h1>

    <form>
      <h3>Login</h3>
      <input type="text"/>
      <h3>Mot de passe</h3>
      <input type="password"/>

      <div class="button_submit">
        <button type="submit">Valider</button>
      </div>
    </form>

  </div>
</template>

<script>
export default {
  name: 'Login',
}
</script>

<style scoped>
.button_submit {
  padding: 20px;
}
</style>

