<template>
  <div id="app">
    <myHeader></myHeader>
    <myGoods></myGoods>
    <myFooter></myFooter>
    <!-- <myCount></myCount> -->
  </div>
</template>

<script>
import myHeader from "./components/MyHeader.vue";
import myGoods from "./components/MyGoods.vue";
import myFooter from "./components/MyFooter.vue";
export default {
  data() {
    return {};
  },
  components: {
    myHeader,
    myGoods,
    myFooter,
    // myCount,
  },
  created() {},

  methods: {},
};
</script>

<style scoped>
#app{
  padding-top: 45px;
}
</style>
