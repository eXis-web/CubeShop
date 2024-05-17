<template>
  <footer class="footer">
    <a class="link footer__author" href="https://armen-varosian-portfolio.netlify.app/" target="_blank">
      Developed with 💻 and ❤️ by <span class="footer__author-name">Ɐrmen</span>
    </a>
    <a class="link footer__source" href="https://github.com/eXis-web/CubeShop" target="_blank">Explore on
      GitHub</a>
  </footer>
</template>

<style lang="scss">
.footer {
  max-width: max-content;
  margin: 0 auto 60px;
  font-size: 0.875rem; /* 14px */
  line-height: 1.25rem; /* 20px */
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 16px;

  &__author,
  &__source {
    @include link-style;
  }
}
</style>
