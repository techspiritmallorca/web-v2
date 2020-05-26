<template>
  <nav class="navbar navbar-expand-lg bg-white navbar-light">
    <div class="container">
      <a class="navbar-brand text-primary" href="index.html">
        <img :src="require('~/assets/logo_100.png')" /> Tech Spirit Mallorca
      </a>
      <div class="collapse navbar-collapse show" id="navbarSupportedContent">
        <div class="ml-auto">
          <a
            class="btn-default btn rounded-pill px-2 social-icon"
            target="_blank"
            href="https://www.youtube.com/channel/UCZKdEQkM595kE23GqSxKbiA"
          >
            <img :src="require(`~/assets/youtube.png`)" alt="YouTube TechSpirit" />
          </a>
          <a
            class="btn-default btn rounded-pill px-2 social-icon"
            target="_blank"
            href="https://twitter.com/techspiritmall1"
          >
            <img :src="require(`~/assets/twitter.png`)" alt="Twitter TechSpirit" />
          </a>
        </div>
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
.navbar-collapse {
  flex: 0 0 auto;
}
.social-icon img {
  height: 30px;
}
</style>
