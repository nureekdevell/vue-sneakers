<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      v-for="item in items"
      :key="item.id"
      :title="item.title"
      :image-url="item.imageUrl"
      :price="item.price"
      :on-click-add="onClickAdd"
    />
  </div>
</template>

<script setup>
import Card from './Card.vue'
defineProps({
  items: Array
})

const onClickAdd = () => {
  alert('Added')
}
</script>

<style scoped></style>
