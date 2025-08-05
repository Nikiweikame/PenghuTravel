<script setup lang="ts">
</script>

<template>  
<header>
    <img alt="penghu logo" class="logo" src="https://www.penghu-nsa.gov.tw/images/content-background.png" />
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/about2">About2</RouterLink>
      </nav>
    </div>
  </header>
</template>

<style scoped lang="scss">

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto;
  width: 100vw;
}



@media (min-width: 1024px) {
}
</style>