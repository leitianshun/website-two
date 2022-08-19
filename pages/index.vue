<template>
  <div>
    <Date></Date>
    <IndexNews></IndexNews>
    <Produce></Produce>
    <Farming></Farming>
    <Enterprice></Enterprice>
  </div>
</template>

<script>
  import Produce from "@/components/Produce.vue";
  import IndexNews from "@/components/IndexNews.vue";
  import Farming from "@/components/Farming.vue";
  import Enterprice from "@/components/Enterprice.vue";
  import Date from "@/components/Date";
  export default {
    name: "IndexPage",
    components: { Date, IndexNews, Produce, Farming, Enterprice },
    data() {
      return {};
    },
  };
</script>
