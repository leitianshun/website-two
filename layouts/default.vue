<template>
  <div>
    <page-header />
    <nuxt class="view-box"></nuxt>
    <page-fooer />
    <ScrollToTop></ScrollToTop>
  </div>
</template>
<script>
  import PageFooer from "../components/PageFooer.vue";
  import PageHeader from "../components/PageHeader.vue";
  import ScrollToTop from "../components/ScrollToTop.vue";

  export default {
    name: "PageDefault",
    components: { PageHeader, PageFooer, ScrollToTop },
    data() {
      return {};
    },
  };
</script>
<style lang="scss" scoped>
  .view-box {
    padding: 0 40px 0;
  }
  @media only screen and (max-width: 450px) {
    .view-box {
      padding: 0 10px;
    }
  }
</style>
