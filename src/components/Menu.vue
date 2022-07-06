<script setup lang="ts">
</script>

<template>
<div class="menu">
    <button class="menu__item">Bakery</button>
    <button class="menu__item">Fruit and vegetables</button>
    <button class="menu__item">Meat and fish</button>
    <button class="menu__item">Drinks</button>
    <button class="menu__item">Kitchen</button>
    <button class="menu__item">Special nutrition</button>
    <button class="menu__item">Baby</button>
    <button class="menu__item">Pharmacy</button>
</div>
</template>

<style lang="scss">
.menu {
    display: flex;
    justify-content: space-around;

    &__item:after {
    content: url(../assets/icons/arrow.svg);
    width: 6.35px;
    height: 2.93px;
    display: inline-block;
    margin-left: 4px;
  }
}
</style>