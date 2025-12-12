<template>
  <div class="box-component">
    <slot />
  </div>
</template>

<script>
export default {
  name: 'BoxComponent',
}
</script>

<style>
.box-component {
  background-color: var(--white);
  border-radius: 20px;
  padding: 20px;
  width: 400px;
  text-align: center;
}
</style>
