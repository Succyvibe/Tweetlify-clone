<template>
  <div>
    <TheNavbar />
    <scrollUpBtn/>
    <Nuxt />
  </div>
</template>

<script>
import TheNavbar from "~/components/TheNavbar.vue";
import scrollUpBtn from "~/components/scrollUpBtn.vue";
export default {
  components: {
    TheNavbar,
    scrollUpBtn
  },
};
</script>
