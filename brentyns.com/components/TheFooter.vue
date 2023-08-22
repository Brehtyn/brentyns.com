<template>
    <footer>
        <div>Brentyn's Minecraft Server</div>
        <div>
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
        </div>
        <div>I really dont know what to put here yet?</div>
    </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
    margin-top: -10px;
    width: 100%;
    display: flex;
    flex-direction: row;
    justify-content: center;
    background: red;
    border-radius: 10px 10px 0 0;
}

footer > div {
    width: 33%;
    min-width: 120px;
    padding: 15px;
    text-align: center;
}
</style>