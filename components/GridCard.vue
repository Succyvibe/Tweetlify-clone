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
  data: {
    features: [
      {
        icon: "5M+ viral tweets",
        title: "Built for speed",
        details:
          "Now you can tweet like a pro! Write high-quality viral tweets in minutes with our viral tweet database.",
      },
      {
        icon: "http://www.w3.org/2000/svg",
        title: "Click and forget",
        details:
          "With our scheduling feature, you can create and schedule tweets with a single click.",
      },
      {
        icon: "http://www.w3.org/2000/svg",
        title: "Accelerate growth",
        details:
          "Automatically engage with your target audience and grow your followers quickly and easily.",
      },
    ],
  },
  components: {
    Card,
  },
};
</script>

<style></style>
