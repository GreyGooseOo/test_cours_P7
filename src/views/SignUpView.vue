<template>
  <div class="about">
    <h1>Création du compte</h1>
    <label for="name">Nom d'utilisateur</label><br>
    <input type="text" id="name" name="name" required maxlength="30"><br>
    <label for="mail">Adresse email</label><br>
    <input type="text" id="mail" name="mail" required maxlength="30"><br>
    <label for="password">Mot de passe</label><br>
    <input type="text" id="password" name="password" requiredmaxlength="30"><br>
    <label for="confPassword">Confirmer le Mot de passe</label><br>
    <input type="text" id="confPassword" name="confPassword" requiredmaxlength="30"><br>
  </div>
</template>

<script>
export default {
}
</script>
