<template>
  <div>

    <the-header />
    <div id="banner">
      <div> Brentyn's Minecraft Server </div>
    </div>
    <NuxtPage />
    <the-footer />

  </div>
</template>

<script>

</script>

<style scoped>
#banner {
  width: 100%;
  height: 350px;
  background-image: url(~/assets/banner.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#banner > div {
  padding-top: 100px;
  text-align: center;
  font-size: 3rem;
  font-family: Minecraft_Title;
  color: azure;
  -webkit-text-stroke: 2.2px black;
  text-shadow: 2px 2px 4px #000;
}
</style>