<template>
  <div>
    <header class="header">
      <p class="header__logo">Dog</p>
      <ul class="gnav">
        <li class="gnav__item">
          <a href="" class="gnav__link">リンクA</a>
        </li>
        <li class="gnav__item">
          <a href="" class="gnav__link">リンクB</a>
        </li>
        <li class="gnav__item">
          <a href="" class="gnav__link">リンクC</a>
        </li>
      </ul>
    </header>
    <div class="main">
      <nuxt />
    </div>
    <footer class="footer">
      <p class="footer__copyright">&copy; Deer, Inc.</p>
    </footer>
  </div>
</template>

<style lang="scss">
.header {
  padding: 16px;
  display: flex;
  justify-content: space-between;
  border-bottom: 1px solid rgba(black, 0.12);
}
.footer {
  border-top: 1px solid rgba(black, 0.12);
  font-size: 13px;
  padding: 16px;
}
.gnav {
  display: flex;
  &__link {
    padding: 8px;
  }
}
</style>
