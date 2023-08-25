<template>
  <div>
    <div id="banner">
      <div> Brentyns Minecraft Server</div>
    </div>

    <div>
      <h1> Hello friends :)</h1>
    </div>

  </div>
</template>

<script>
export default {};
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
  width: 100%;
  padding-top: clamp(1em, 1.3em, 2em);
  text-align: center;
  font-size: clamp(3rem, 3.5rem, 5rem);
  font-family: Minecraft_Title;
  color: azure;
  -webkit-text-stroke: 2.2px black; 
}
</style>