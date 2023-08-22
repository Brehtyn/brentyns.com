<template>
  <header>
    <nav>
      <ul>
        <NuxtLink to="/">
          <li>Home</li>
        </NuxtLink>
        <NuxtLink to="/map">
          <li>Map</li>
        </NuxtLink>
        <NuxtLink to="/about">
          <li>About</li>
        </NuxtLink>
        <NuxtLink to="/contact">
          <li>Contact</li>
        </NuxtLink>
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
  width: 100vw;
  background: rgba(0, 0, 0, 0.777);
}

nav {
  margin: 0 auto;
}

ul {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  list-style: none;
}

li {
  padding: 10px;
  font-weight: 100;
  color: #fff;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
  color: azure;
}

</style>