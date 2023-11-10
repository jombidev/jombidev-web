<script setup>
import InstagramIcon from "@/icons/InstagramIcon.vue";
import TwitterIcon from "@/icons/TwitterIcon.vue";
import GithubIcon from "@/icons/GithubIcon.vue";
</script>

<template>
  <header>
  </header>

  <main>
    <div class="main">
      <img alt="bocchi kawaii" class="profile_img" src="/bocchi.png">
      <h1>Jombi</h1>
      <p class="description-text">The Evolving Backend Developer</p>
      <div>
        <a href="https://instagram.com/jombidev" class="icons">
          <InstagramIcon/>
        </a>
        <a href="https://x.com/jombidev" class="icons">
          <TwitterIcon/>
        </a>
        <a href="https://github.com/jombidev">
          <GithubIcon/>
        </a>
      </div>
    </div>
  </main>
</template>

<style scoped>


@font-face {
  font-family: 'LINESeedKR-Bd';
  src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_11-01@1.0/LINESeedKR-Bd.woff2') format('woff2');
  font-weight: 700;
  font-style: normal;
}

main {
  font-family: LINESeedKR-Bd, Arial, sans-serif;
  --impact-color: #ff2291;
  --main-color: #fff000;
}
.profile_img {
  width: 200px;
  height: 200px;
}
.description-text {
  padding-bottom: 10px;
}
.icons {
  padding-right: 20px;
}
.main {
  position: absolute;
  top: 50%;
  left: 50%;
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  width: 40%;
  text-align: center;
}
</style>