<template>
  <div>
    <HeaderVue />
    <ImageDisplay />
    <Features />
    <TweetTool />
    <EngagementTool />
    <AutomationFeature />
    <Schedule />
    <Growth />
    <Pricing />
    <CTA />
    <FooterVue />
  </div>
</template>

<script>
import HeaderVue from "~/components/HeaderVue.vue";
import ImageDisplay from "~/components/ImageDisplay.vue";
import Features from "~/components/Features.vue";
import TweetTool from "~/components/TweetTool.vue";
import EngagementTool from "~/components/EngagementTool.vue";
import AutomationFeature from "~/components/AutomationFeature.vue";
import Schedule from "~/components/Schedule.vue";
import Growth from "~/components/Growth.vue";
import Pricing from "~/components/Pricing.vue";
import CTA from "~/components/CTA.vue";
import FooterVue from "~/components/FooterVue.vue";

export default {
  name: "IndexPage",
  components: {
    HeaderVue,
    ImageDisplay,
    Features,
    TweetTool,
    EngagementTool,
    AutomationFeature,
    Schedule,
    Growth,
    Pricing,
    CTA,
    FooterVue,
  },
};
</script>
