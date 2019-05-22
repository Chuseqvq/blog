<template>
  <div class="box">
    <HelloWorld/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    HelloWorld
  }
};
</script>
<style lang="scss" scoped>
.box {
  display: flex;
  width: 100%;
  height: 80vh;
  align-items: center;
  justify-content: center;
}
</style>
