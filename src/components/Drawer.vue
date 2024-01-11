<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black opacity-70 z-10"></div>
  <div class="fixed top-0 right-0 h-full w-96 bg-white z-20 p-10">
    <DrawerHead />
    <CartItemList />

    <div class="flex flex-col gap-6 my-7">
      <div class="flex gap-2">
        <span>Итого</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12900 $</b>
      </div>
      <div class="flex gap-2">
        <span>Налог</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>900 $</b>
      </div>
    </div>
    <button
      disabled=""
      class="transition cursor-pointer disabled:bg-slame-300 bg-lime-500 w-full py-3 hover:bg-lime-600 active:bg-lime-700 text-white rounded-xl"
    >
      Оформить заказ <img src="../" alt="" />
    </button>
  </div>
</template>

<script setup>
import DrawerHead from './DrawerHead.vue'
import CartItemList from './CartItemList.vue'
</script>

<style scoped></style>
