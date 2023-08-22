<template>
  <div>
    <div id="banner">
      <div> Brentyns Minecraft Server</div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
#banner {
  width: 100vw;
  height: 350px;
  background-image: url(~/assets/banner.jpg);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#banner > div {
  width: 100vw;
  padding-top: clamp(1em, 1.5em, 2em);
  text-align: center;
  font-size: clamp(3.5rem, 6vw, 5rem);
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: azure;
  -webkit-text-stroke: 2.2px black; 
}
</style>