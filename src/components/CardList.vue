<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские Кроссовки Nike Blazer Mid Suede"
      image-url="/sneakers/sneakers-1.jpg"
      :price="5000"
      is-favorite="true"
      :on-click-add="onClickAdd"
    />
  </div>
</template>

<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('Added')
}
</script>

<style scoped></style>
