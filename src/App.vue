<template>
  <MacBookPro />
</template>

<script>
import MacBookPro from "@/views/MacBookPro.vue";

export default {
  name: "App",
  components: {
    MacBookPro,
  },
};
</script>

<style lang="scss">
body {
  margin: 0;
}

#app {
  font-family: "SF Pro Display", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
