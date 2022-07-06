<script setup lang="ts">
import SearchForm from './SearchForm.vue';
</script>

<template>
  <header>
    <div class="header__top-content">
      <div>
        <a class="header__link header__link__green">Chat with us</a>
        <a class="header__link header__link__black">+420 336 775 664</a>
        <a class="header__link header__link__black">info@freshnesecom.com</a>
      </div>
      <div>
        <a class="header__link header__link__green">Blog</a>
        <a class="header__link header__link__green">About Us</a>
        <a class="header__link header__link__green">Careers</a>
      </div>
    </div>
    <div class="header__bottom-content">
      <div class="header__logo"></div>
      <SearchForm class="header__search-form"/>
      <div class="header__buttons">
        <div class="header__button header__button__account"></div>
        <div class="header__button header__button__basket"></div>
      </div>
    </div>
  </header>
</template>

<style lang="scss" scoped>
@import "../assets/colors.scss";
@import "../assets/fonts.scss";

.header {
  &__top-content {
    display: flex;
    justify-content: space-between;
    margin: 16px 0;
  }

  &__bottom-content {
    display: flex;
    justify-content: space-between;
    margin: 40px 0;
  }

  &__link:not(:last-child) {
    margin-right: 35px;
  }

  &__link__green {
    color: $green-800;
  }

  &__link__black {
    color: $black-900;
  }

  &__logo {
    background: url(../assets/icons/Freshnesecom.svg);
    width: 177px;
    height: 18px;
    margin: 16px 0;
  }

  &__search-form {
  }

  &__buttons {
    display: flex;
  }

  &__button {
    width: 24px;
    height: 24px;
  }

  &__button__account {
    background: url(../assets/icons/ic-actions-user.svg);
    margin-right: 40px;
  }

  &__button__basket {
    background: url(../assets/icons/ic-ecommerce-basket.svg);
  }
}
</style>
