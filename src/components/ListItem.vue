<template>
  <div class="list-item">
    <list-item-avatar :src="item.src" />
    <list-item-title :title="item.nombre" />
  </div>
</template>

<script>
export default {
  name: 'ListItem',
  props: {
    item: {
      type: Object,
      required: true,
    },
  },
}
</script>

<style>
.list-item {
  display: flex;
  flex-direction: row;
  justify-content: left;
  align-items: center;
}
</style>
