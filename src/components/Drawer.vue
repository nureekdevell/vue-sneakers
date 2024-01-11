<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black opacity-70 z-10"></div>
  <div class="fixed top-0 right-0 h-full w-96 bg-white z-20 p-10">
    <DrawerHead />
    <CartItem />
    <CartItem />
    <CartItem />
    <CartItem />
  </div>
</template>

<script setup>
import DrawerHead from './DrawerHead.vue'
import CartItem from './CartItem.vue'
</script>

<style scoped></style>
