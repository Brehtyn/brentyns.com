<template>
    <footer>
        <div>
            <h1>
                Brentyns Minecraft Server
            </h1>
            <p>
                Come on grab your friends <br>
                We'll go to very distant lands!
            </p>
        </div>
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
        <div>
            <nav>
                <NuxtLink to="https://github.com/Brehtyn/brentyns.com"> <img src="~/assets/logo_github.png" alt="github logo"/> </NuxtLink>
                <NuxtLink to="https://ibigital.com"> <img src="~/assets/logo_simple_bigital_inverted.jpg" alt="ibigital logo inverted"/> </NuxtLink>
                <NuxtLink to="https://brentyn.net"> <img src="~/assets/heart.png" alt="heart"/> </NuxtLink>
                <NuxtLink to="https://www.minecraft.net/en-us/about-minecraft"> <img src="~/assets/logo_minecraft.png" alt="minecraft logo"/> </NuxtLink>
            </nav>
            <div>
                Made and lovingly maintained by <NuxtLink to="https://brentyn.net"> Brentyn Hanna</NuxtLink>
            </div>
        </div>
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
    justify-content: space-evenly;
    background: rgba(0, 0, 0);
    border-radius: 10px 10px 0 0;
    color: rgba(255, 255, 255, 0.80);
    font-family: Minecraft_Body;
}

img {
    height: 30px;
    padding: 10px;
    width: auto;
}

footer>div {
    width: clamp(120px, 33%, 250px);
    padding: 2em .5em .5em .5em ;
    text-align: left;
    flex-wrap: nowrap;
}

footer>div:nth-child(1)>h1 {
    font-family: Minecraft_Title;
    font-size: 1.5em;
    padding-bottom: 1rem;
}

footer>div:nth-child(2)>nav>ul>a {
    text-align: center;
    text-decoration: none;
    list-style-type: none;
    color: rgba(255, 255, 255, 0.80);
}

footer>div:nth-child(2)>nav>ul>a>li {
    padding: 5px;
}

@media screen and (max-width: 850px) {
    footer {
        flex-wrap: wrap;
    }

    footer > div {
        width: auto;
        min-width: unset;
        text-align: center;
    }
}
</style>