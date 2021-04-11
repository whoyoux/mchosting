<template>
  <header class="w-full">
    <div class="hidden md:block md:absolute top-0 right-0 h-full bg"></div>

    <nav
      class="flex md:flex-row md:text-left flex-col justify-items-center align-middle justify-between min-w-0 mx-10 text-center py-10 md:p-10"
    >
      <p class="text-5xl font-medium cursor-pointer title">mchosting</p>
      <ul
        class="flex text-2xl flex-col md:flex-row md:align-middle items-center gap-5"
      >
        <li class="hover:underline cursor-pointer">plans</li>
        <li class="hover:underline cursor-pointer">dashboard</li>
        <li class="hover:underline cursor-pointer">account</li>
      </ul>
    </nav>

    <div class="md:flex md:flex-row md:w-full md:px-20 header-hero">
      <div class="w-4/5 md:w-full text-left mx-auto md:flex md:items-center">
        <div>
          <h1
            class="text-6xl font-bold w-3/4 mx-auto text-center md:pt-38 md:mx-0 md:text-left 2xl:w-8/12 mb-5"
          >
            Minecraft hosting right for you
          </h1>
          <h3
            class="text-3xl mt-2 w-3/4 mx-auto text-center md:mx-0 md:w-full md:text-left"
          >
            Just choose your plan and start play!
          </h3>
          <div class="hidden py-5 md:block md:w-1/2">
            <img
              src="../assets/img/scroll-down.svg"
              width="30"
              class="mx-auto"
            />
          </div>
        </div>
      </div>
      <div class="hidden md:w-full md:grid md:place-items-center">
        <img src="../assets/img/dirt.png" alt="dirt" class="h-auto w-1/2" />
      </div>
    </div>

    <div class="text-center mt-8">
      <h1 class="text-4xl font-medium">Plans</h1>
    </div>
  </header>
</template>

<script>
export default {}
</script>

<style lang="postcss" scoped>
/* nav {
  height: 10vh;
} */

.bg {
  width: 60vw;
  height: 100vh;
  z-index: -10;
  background: url('../assets/img/bg.svg');
  background-size: cover;
}

@media (min-width: 768px) {
  nav {
    height: 15vh;
  }
  .header-hero {
    height: 60vh;
    margin-bottom: 25vh;
  }
}

/* @media (min-width: 1024px) {
  
}

@media (min-width: 1280px) {
  
}

@media (min-width: 1536px) {
  
} */
</style>
