<template>
  <header>
    <nav>
      <ul>
        <NuxtLink to="/"> <li>Home</li> </NuxtLink>
        <NuxtLink to="/map"> <li>Map</li> </NuxtLink>
        <NuxtLink to="/about"> <li>About</li> </NuxtLink>
        <NuxtLink to="/contact"> <li>Contact</li> </NuxtLink>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  position: fixed;
  top: 0;
  left: 0;
  background: red;
  width: 100vw;
}
nav {
  margin: 0 auto;
}
ul {
    margin: 0;
    padding: 0;
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    list-style: none;
}
li {
    padding: 10px;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #fff;
}
a {
    text-decoration: none;
}
</style>