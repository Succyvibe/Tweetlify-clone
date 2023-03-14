<template>
  <section class="bg-[#212630] mt-[400px] lg:mt-0 py-48">
    <div class="lg:max-w-[1216px] mx-auto px-4">
      <div class="w-full md:max-w-4xl text-start mb-16 md:mx-auto">
        <h2 class="text-[2.9rem] text-[#F4F4F5] font-[900] leading-[50px]">
          Make your Twitter game zen with these tools
        </h2>
        <p class="text-[#D1D5DB] text-[1.5rem] leading-[2rem] relative my-10">
          Speed your way to success with our product
        </p>
      </div>
      <GridCard />
    </div>
  </section>
</template>

<script>
import GridCard from "./GridCard.vue";
export default {
  components: {
    GridCard,
  },
};
</script>
