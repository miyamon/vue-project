<script setup lang="ts"></script>

<template>
  <div class="sidebar-links">
    <div class="sidebar-links__title">Header name</div>
    <a class="sidebar-links__item">name</a>
    <a class="sidebar-links__item">name</a>
    <a class="sidebar-links__item">name</a>
    <a class="sidebar-links__item">name</a>
    <a class="sidebar-links__item">name</a>
    <a class="sidebar-links__button">name</a>
  </div>
</template>

<style lang="scss">
@import "../assets/colors.scss";
.sidebar-links {
  flex-flow: column;
  display: flex;
  &__title {
    font-family: "Poppins";
    font-style: normal;
    font-weight: 600;
    font-size: 18px;
    line-height: 27px;
    color: $black-900;
  }

  &__item {
    font-family: "Open Sans";
    font-style: normal;
    font-weight: 400;
    font-size: 14px;
    line-height: 19px;
    text-decoration-line: underline;
    color: $green-800;
  }
  &__button {
    background: $black-300;
    border-radius: 12px;
    font-family: "Poppins";
    font-style: normal;
    font-weight: 700;
    font-size: 15px;
    line-height: 22px;
    color: $black-900;
    padding: 12.5px 16px;
    border-radius: 12px;
    width: fit-content;
  }
}
</style>
