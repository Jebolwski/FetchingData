<template>
  <div id="nav">
    <div class="left">
      <ul>
        <li>Anasayfa</li>
        <li>Keşfet</li>
        <li>Bildirimler</li>
        <li>Mesajlar</li>
        <li>Yer İşaretleri</li>
        <li>Listeler</li>
        <li><router-link to="/profil">Profil</router-link></li>
        <li>Daha Fazla</li>
        <li><button>Tweetle</button></li>
        <li class="button">Mert Gökmen</li>
      </ul>
    </div>
    <router-view />
  </div>
</template>
<script>
export default {
  name: "Home",
};
</script>
<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Mukta", sans-serif;
  font-weight: 700;
}

.left {
  position: fixed;
  width: 24vw;
  left: 0;
  top: 0;
  height: 100vh;
  background-color: rgb(151, 224, 41);
}

ul {
  display: grid;
  margin-top: 10vh;
  list-style: none;
  text-align: center;
  color: white;
  font: 4em;
}

li {
  margin-top: 28px;
}
</style>
