<template>
  <header class="flex justify-between border-b border-slate-200 px-8 py-8">
    <div class="flex justify-between items-center gap-4">
      <img src="/logo.png" alt="Logo" class="w-10" />
      <div>
        <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
        <p class="text-slate-400">Магазин лучших крассовок</p>
      </div>
    </div>

    <ul class="flex items-center gap-8">
      <li class="flex items-center cursor-pointer text-gray-500 gap-3 hover:text-black">
        <img src="/cart.svg" alt="cart" />
        <b>1205 руб</b>
      </li>
      <li class="flex items-center cursor-pointer text-gray-500 gap-3 hover:text-black">
        <img src="/heart.svg" alt="cart" />
        <span>Закладки</span>
      </li>
      <li class="flex items-center cursor-pointer text-gray-500 gap-3 hover:text-black">
        <img src="/profile.svg" alt="cart" />
        <span>Профиль</span>
      </li>
    </ul>
  </header>
</template>

<script setup></script>

<style scoped></style>
