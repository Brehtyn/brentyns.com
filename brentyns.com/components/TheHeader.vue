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
  width: 100%;
  background: rgba(0, 0, 0);
  font-family: Minecraft_Body;
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
  padding: 1rem;
  font-weight: 100;
  color: #fff;
  color: azure;
}

</style>