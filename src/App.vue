<script setup>
  import ButtonVue from './components/Button.vue';
</script>

<style>
.speed-350ms {
  animation-delay: 350ms;
}

.speed-450ms {
  animation-delay: 450ms;
}

.speed-550ms {
  animation-delay: 550ms;
}
</style>

<template>
  <div class="flex h-screen justify-center items-center bg-zinc-900">
    <div class="text-center">
      <h1 class="text-6xl font-bold text-white animate__animated animate__fadeInDown font-family">THIS IS A WONG</h1>
      <img src="https://hips.hearstapps.com/digitalspyuk.cdnds.net/16/32/1470845049-computer-typing-gif.gif?resize=980:*" alt="typing" class="object-cover h-48 w-96 animate__animated animate__fadeIn speed-450ms">
      <div class="flex justify-center m-3 text-white animate__animated animate__fadeInDown">
        <h2 class="mx-3 animate__animated animate__fadeIn speed-350ms">Coffee ☕</h2> <i class="fa-solid fa-slash-forward flex items-center"></i>
        <h2 class="mx-3 animate__animated animate__fadeIn speed-450ms">Typing 📃</h2> <i class="fa-solid fa-slash-forward flex items-center"></i>
        <h2 class="mx-3 animate__animated animate__fadeIn speed-550ms">Leetode 💻</h2>
      </div>
      <div class="grid gap-4 grid-cols-1 grid-rows-12 md:grid-cols-3 animate__animated animate__fadeInDown">
        <ButtonVue href="https://github.com/S0l0Mont" target="_blank" rel="noreferrer">
          <i class="fab fa-github mr-3"></i> 
          GitHub
        </ButtonVue>
        <ButtonVue href="https://www.youtube.com/channel/UCgKRAftgXpOdNawFd_WC7lQ" target="_blank" rel="noreferrer">
          <i class="fab fa-youtube mr-3"></i> 
          YouTube
        </ButtonVue>
        <ButtonVue href="mailto:wong@thisisawong.wang" target="_blank" rel="noreferrer">
          <i class="fas fa-envelope mr-3"></i> 
          E-mail
        </ButtonVue>
        <ButtonVue href="" target="_blank" rel="noreferrer">
          <i class="fas fa-briefcase mr-3"></i>
          Résumé
        </ButtonVue>
        <ButtonVue href="https://docs.google.com/document/d/1UFfhF1hyCvt26VexQc7NCWb8tENbzaAUe_Q6BbTU4zo/edit?usp=sharing" target="_blank" rel="noreferrer">
          <i class="fa-sharp fa-light fa-file mr-3"></i>
          FAQ
        </ButtonVue>
      </div>
      <div>

      </div>
    </div>
  </div>
</template>