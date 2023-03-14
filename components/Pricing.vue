<template>
  <section class="bg-[#2A303C] mt-[400px] lg:mt-0 py-48">
    <div class="lg:max-w-[1216px] mx-auto px-4">
      <div class="w-full md:max-w-4xl text-center mb-16 md:mx-auto">
        <h2 class="text-[2.9rem] text-[#F4F4F5] font-[900] leading-[50px]">
          Pricing
        </h2>
        <p class="text-[#D1D5DB] text-[1.5rem] leading-[2rem] relative my-8">
          Simple and flexible. Cancel anytime.
        </p>
        <div class="flex justify-center">
          <button class="text-sm font-semibold text-[#D1D5DB]">
            Billed Monthly
          </button>
          <IoToggle />
          <button class="text-sm font-semibold text-[#D1D5DB]">
            Billed Yearly
          </button>
        </div>
      </div>

      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8 px-4 lg:px-0">
        <PriceCardFree />
        <PriceCardMonthly />
        <PriceCardYearly />
      </div>
    </div>
  </section>
</template>

<script>
import PriceCardFree from "./PriceCardFree.vue";
import PriceCardMonthly from "./PriceCardMonthly.vue";
import PriceCardYearly from "./PriceCardYearly.vue";
export default {
  components: {
    PriceCardFree,
    PriceCardMonthly,
    PriceCardYearly,
  },
};
</script>
