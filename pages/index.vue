<template>
  <div id="wrapper">
    <HeroSection />
  </div>
</template>

<style lang="scss">
#wrapper {
  /* decimal value is aspect ratio of background image */
  max-width: min(calc(100vh * 1.6));
  display: flex;
  flex-direction: column;
  align-items: center;
  margin: 0 auto;
}
</style>
