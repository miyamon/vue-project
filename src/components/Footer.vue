<script setup lang="ts"></script>

<template>
  <footer>
    <div class="footer__links">
      <div class="footer__links-column">
        <div class="footer__links-header">Get in touch</div>
        <a class="footer__links-item">About Us</a>
        <a class="footer__links-item">Careers</a>
        <a class="footer__links-item">Press Releases</a>
        <a class="footer__links-item">Blog</a>
      </div>
      <div class="footer__links-column">
        <div class="footer__links-header">Connections</div>
        <a class="footer__links-item">Facebook</a>
        <a class="footer__links-item">Twitter</a>
        <a class="footer__links-item">Instagram</a>
        <a class="footer__links-item">Youtube</a>
        <a class="footer__links-item">LinkedIn</a>
      </div>
      <div class="footer__links-column">
        <div class="footer__links-header">Earnings</div>
        <a class="footer__links-item">Become an Affiliate</a>
        <a class="footer__links-item">Advertise your product</a>
        <a class="footer__links-item">Sell on Market</a>
      </div>
      <div class="footer__links-column">
        <div class="footer__links-header">Account</div>
        <a class="footer__links-item">Your account</a>
        <a class="footer__links-item">Returns Centre</a>
        <a class="footer__links-item">100 % purchase protection</a>
        <a class="footer__links-item">Chat with us</a>
        <a class="footer__links-item">Help</a>
      </div>
    </div>
    <div class="footer__tags">
      <div>Product tags</div>
      <div>
        <div class="footer__tags-item">tag</div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
@import "../assets/colors.scss";
.footer {
  &__links {
    display: flex;
    justify-content: space-between;
  }

  &__links-column {
    display: flex;
    flex-direction: column;
  }

  &__links-header {
  }

  &__links-item {
    color: $green-800;
  }

  &__tags {
  }

  &__tags-item {
    background: $black-300;
    padding: 4px 10px;
    border-radius: 12px;
    width: fit-content;
  }
}
</style>
