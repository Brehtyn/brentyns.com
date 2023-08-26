<template>
  <div>
    <div id="intro">
      <div>
        <h1>Come on, grab your friends!</h1>
        <p>
          Joining a little community of nerdy crafters doesn't get any easier
          than this! <br />
          <br />

          Highly avaliable 24/7 bedrock minecraft server. View
          our <NuxtLink to="about"> about page </NuxtLink> for more details.
        </p>
      </div>

      <div>
        <img
          src="~/assets/island.png"
          alt="minecraft island with many phantoms inbound"
          max-width="100%"
        />
      </div>
    </div>

    <div id="server_banner">
      <h2>Online Status</h2>
      <p>Minecraft Server :</p>

      <p>Players Online :</p>
    </div>

    <div id="map_section">
      <div>
        <p>
          Embrace new adventures more readily by never again feeling the string
          of losing that spicy cave system or newly built mansion. <br />
          <br />
          Find yourself (or your foes!) with an interative online map that is
          updated regularly.
        </p>

        <NuxtLink to="/map"> <button>Take a look now!</button> </NuxtLink>
      </div>
    </div>

    <div id="contact">
        <img
          src="~/assets/skelly.png"
          alt="minecraft skeleton with big eyes"
          max-width="100%"
        />
      <div>
        <h3>Get in touch?</h3>
        <p>
          Have a burning question or a serious concern you need to contact me
          with? Head on over to the
          <NuxtLink to="contact">contact page</NuxtLink>
          to get more assitance.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: "About page",
    };
  },
};
</script>

<style>
#intro {
  width: 100%;
  padding: 1rem 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  font-size: 1.2rem;
}
#intro > div {
  text-align: center;
}
#intro > div:nth-child(1) {
  padding: 4rem .5rem 2rem .5rem;
  width: 400px;
  text-shadow: 2px 2px #000;
}
#intro > div:nth-child(1) > h1 {
  padding: 2rem;
  letter-spacing: 5px;
  font-family: Minecraft_Body;
}
#intro > div:nth-child(2) > img {
  max-width: 100%;
}

#server_banner {
  width: 100%;
  background: black;
  text-align: center;
  letter-spacing: 3px;
  font-size: 1.3rem;
  padding: 4rem 0;
  margin: 4rem auto;
}

#map_section {
  width: 400px;
  max-width: 100%;
  height: auto;
  margin: 4rem auto;
}
#map_section > div {
  width: 100%;
  height: fit-content;
  text-align: center;
  background-image: url(~/assets/map.png);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#map_section > div > p {
  text-align: left;
  padding: 3rem 3rem 2rem 3rem;
  font-size: 1.2rem;
}
#map_section > div > a > button {
  margin: 1rem;
  margin-bottom: 4rem;
  border-radius: 4px;
  padding: 1rem;
  font-family: Minecraft_Title;
  font-size: 1.2rem;
  color: #000;
  background-image: linear-gradient(#000 #fff #000);
}
#map_section > div > a > button:hover {
  background-color: chartreuse;
}
#map_section > div > a > button:active {
  background-color: green;
  color: white;
}

#contact {
  margin: 4rem auto;
  display: flex;
  justify-content: center;
  flex-direction: row;
  flex-wrap: wrap;
  width: 100%;
  height: fit-content;
}
#contact > div {
  padding: 3rem 1rem;
  width: clamp(300px, 30%, 100%);
  text-shadow: 2px 2px 4px #000;
  font-size: 1.1rem;
}
#contact > div > h3 {
  letter-spacing: 3px;
}
#contact > div > p {
  padding: 1rem 0;
}
#contact > img {
  padding: 0;
  margin: 0;
  width: 100px;
  height: auto;
}
</style>