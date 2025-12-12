<template>
  <BoxComponent>
    <img src="./assets/image-qr-code.png" alt="QR Code" />
    <h1>
      Improve your front-end skills by building projects
    </h1>
    <div class="qr-text">
      Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
    </div>
  </BoxComponent>
</template>

<script>
import BoxComponent from './components/BoxComponent.vue';

export default {
  name: 'App',
  components: {
    BoxComponent,
  }
}
</script>

<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  img {
    width: 100%;
    height: auto;
    border-radius: 15px;
  }
  h1 {
    color: var(--color-heading);
  }
</style>
