<template>
  <div class="container"></div>
</template>

<script>
export default {
  name: "home",
  components: {},
  data() {
    return {};
  },
  created() {
    console.log("home created");
  },
  mounted() {
    console.log("home mounted");
  },
};
</script>
<style scoped lang="less">
@color: rgb(112, 222, 141);
.container {
  position: relative;
  width: 100%;
  height: 100%;
  background: @color;
}
</style>
