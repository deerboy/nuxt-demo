<template>
  <div>
    <div class="hero">
      <p class="hero__title">はじめてのNuxtサイト</p>
      <p class="hero__description">Nuxtを覚えよう</p>
      <p class="hero__btn">
        <a href="" class="btn btn--white">リンク</a>
      </p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.hero {
  height: 600px;
  padding: 0 24px;
  display: flex;
  flex-flow: column;
  justify-content: center;
  background: #000;
  color: #ffffff;
  background: center/cover url('/hero.jpg');
  &__title {
    margin-bottom: 16px;
    font-size: 40px;
    font-weight: bold;
  }
  &__description {
    font-size: 16px;
    line-height: 1.8;
    margin-bottom: 24px;
  }
  @include sp {
    height: 400px;
  }
}
</style>
