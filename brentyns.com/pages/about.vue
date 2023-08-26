<template>
    <div>
        <div id="intro">
            <div>
                <h1>Server Info:</h1>
                <h3>
                    Before you get the IP and Port information below, I just ask you take
                    a quick second to read our code of conduct :
                </h3>
                <p>
                    <i> Please do not be a jerk. </i> That is really the only rule. I am
                    trying to run this server frugally with an incredibly open door.

                    <br />
                    <br />

                    However, if people are creating lag machines, destroying creations, or
                    just in general constantly ruining other player's experiences, I will
                    implement harsher server settings and ban offenders.

                    <br />
                    <br />

                    <b>
                        These terms are accepted by connecting to the Minecraft server and
                        must be followed at all times.
                    </b>
                </p>
            </div>

            <img src="~/assets/creeper.png" alt="minecraft creeper art with red eyes" />
        </div>

        <div id="content">
            <h2>Server Information</h2>
            Name : Brentyn's Server
            <br />
            <br />
            Server Address: craft.brentyns.com
            <br />
            <br />
            Port: 19139
        </div>

        <div id="rules">
            <h3>Server Gamerules</h3>
            <ul>
                <li>Gamemode : Survival</li>
                <li>Difficulty : Normal</li>
                <li>Whitelist : False</li>
                <li>Cheats : False</li>
                <li>Mob Griefing : False</li>
                <li>Fall Damage : False</li>
                <li>Keep Inventory : True</li>
                <li>Instant Respawn : True</li>
                <li>Show Coordinates : True</li>
                <li>Weather : True</li>
                <li>Daycycle : True</li>
                <li>Fire Spread : True</li>
                <li>Explosions : True</li>
            </ul>
        </div>

        <div id="content">
            <h2>Server Mods</h2>
            None... <i> yet</i>
        </div>

    </div>
</template>
 
<style scoped>
#intro>div>h1,
#intro>div>h3,
#intro>div>p {
    text-align: left;
    padding: 1rem;
}

#intro>div>h3 {
    padding: 0 1rem;
    font-family: Minecraft_Body;
}

#intro>img {
    padding: 10rem 4rem;
    width: 200px;
    max-width: 100%;
    height: fit-content;

}

#content {
    text-align: center;
    margin: 4rem auto;
    padding: 2rem 0;
    width: clamp(290px, 35%, 500px);
    background-image: linear-gradient(to left, #051937, #004d7a, #008793, #00bf72, #a8eb12);
    border-radius: 30px;
}

#rules {
    margin: 4rem auto;
    padding: 2rem 0;
    width: clamp(290px, 35%, 500px);
    background-image: linear-gradient(to right, #051937, #004d7a, #008793, #00bf72, #a8eb12);
    border-radius: 30px;
}

#content > h2, #rules > h3 {
    padding-bottom: 1rem;
    text-align: center;
    letter-spacing: 3px;
    font-size: 1.3rem;
    text-shadow: 2px 2px #000;
}

#rules>ul {
    width: fit-content;
    padding: 0;
    margin: 0 auto;
}

#rules>ul>li {
    padding: .5rem;
}
</style>