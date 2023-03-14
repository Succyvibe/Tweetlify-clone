<template>
  <div>
    <HeaderVue />
    <ImageDisplay />
    <Features />
    <TweetTool />
    <EngagementTool />
  </div>
</template>

<script>
import HeaderVue from "~/components/HeaderVue.vue";
import ImageDisplay from "~/components/ImageDisplay.vue";
import Features from "~/components/Features.vue";
import TweetTool from "~/components/TweetTool.vue";
import EngagementTool from "~/components/EngagementTool.vue";

export default {
  name: "IndexPage",
  components: {
    HeaderVue,
    ImageDisplay,
    Features,
    TweetTool,
    EngagementTool,
  },
};
</script>
