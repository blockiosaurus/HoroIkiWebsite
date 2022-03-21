<template>
  <div class="footer pt-1 pb-1">
    <p class="px-3">Built with</p>
    <i class="nes-icon heart"></i>
    <p class="px-3">
      by
      <a
        class="nes-text is-primary"
        href="https://horoikimono.com"
        target="_blank"
        >HOROIKIMONO DEV</a
      >
      | powered by
      <span
        class="nes-text is-primary"
       
        >gemworks</span
      >
    </p>
    <img src="../../assets/gg_logo.png" height="31" width="28" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  @apply w-full flex justify-center align-middle bg-gray-200 text-center;
  position: absolute;
  bottom: 0px;
  height: 40px;
}
</style>
