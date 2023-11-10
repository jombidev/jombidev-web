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
      <h1>Jombi</h1>
      <p>Evolving Backend Developer</p>
      <div class="item-list">
        <a href="https://instagram.com/jombidev">
          <InstagramIcon/>
        </a>
        <a href="https://x.com/jombidev">
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
main {
  font-family: Arial, sans-serif;
  --impact-color: #ff2291;
  --main-color: #fff000;
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