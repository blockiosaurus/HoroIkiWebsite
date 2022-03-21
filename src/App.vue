<template>
  <div class="relative h-full min-h-screen bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 .">
    <TheNavBar />
    <div class="italic mt-5 text-center text-white">WELCOME TO NOROIKIMONO STAKING</div>
    <img src="./assets/logo.png"  class="mx-auto mt-10" />
    <div class="p-10 bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500 .">
      <router-view />
    </div>

    <div class="pt-10"></div>
    <TheCat />
    <TheFooter />
  </div>
</template>

<script>
import TheNavBar from '@/components/TheNavBar';
import TheFooter from '@/components/gem-farm/TheFooter';
import TheCat from '@/components/gem-farm/TheCat';
export default {
  components: { TheCat, TheFooter, TheNavBar },
};
</script>

<style>
* {
  font-family: 'Press Start 2P', monospace;
}
input[type='radio']:checked + span {
  @apply text-black;
}
</style>
