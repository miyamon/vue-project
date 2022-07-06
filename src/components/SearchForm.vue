<script setup lang="ts"></script>
<template>
  <div class="search-form">
    <button class="search-form__dropdown">
      All categories
    </button>
    <input
      placeholder="Search Products, categories"
      class="search-form__input"
    />
    <button class="search-form__search-icon">
    </button>
  </div>
</template>
<style lang="scss" scoped>
@import "../assets/colors.scss";
.search-form {
  background-color: $black-100;
  width: 500px;
  border: 1px solid $black-500;
  border-radius: 12px;
  display: flex;
  padding: 11px 0;
  align-items: center;

  &__dropdown {
    width: 170px;
    border-right: 1px solid $black-500
  }

  &__dropdown:after {
    content: url(../assets/icons/arrow.svg);
    width: 6.35px;
    height: 2.93px;
    display: inline-block;
    margin-left: 12px;
  }

  &__input {
    width: 270px;
    padding-left: 25px;
  }

  &__search-icon {
    background: url(../assets/icons/search-icon.svg);
    width: 16px;
    height: 16px;
  }
}
</style>
