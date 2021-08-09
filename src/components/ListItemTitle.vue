<template>
  <p class="name">{{ title }}</p>
</template>

<script>
export default {
  name: 'ListItemTitle',
  props: {
    title: {
      type: String,
      required: true,
    },
  },
}
</script>

<style>
.name {
  color: green;
  font-weight: bold;
}
</style>
