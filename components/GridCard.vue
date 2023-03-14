<template>
  <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 px-4 lg:px-0">
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
  </div>
</template>

<script>
import Card from "@/components/Card.vue";
export default {
  components: {
    Card,
  },
};
</script>

<style></style>
