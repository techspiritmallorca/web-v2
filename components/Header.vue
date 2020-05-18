<template>
  <nav class="navbar navbar-expand-lg bg-white navbar-light">
    <div class="container">
      <a class="navbar-brand text-primary" href="index.html"><img :src="require('~/assets/logo_100.png')"/> Tech Spirit Mallorca</a>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <a
          class="btn-default btn rounded-pill px-4 ml-auto"
          href="https://shop.startbootstrap.com/sb-ui-kit-pro"
        >
          Contactar
          <i class="fas fa-arrow-right ml-1"></i>
        </a>
      </div>
    </div>
  </nav>
</template>
<style lang="scss">
.navbar-brand {
  img {
    height: 45px;
  }
}
</style>
