<template>
  <div id="app">
    <MyName :myName="name" />
  </div>
</template>

<script>
import MyName from "@/components/MyName.vue";
export default {
  name: "app",
  data() {
    return {
      name: "Nwulu Uchechukwu Prince",
    };
  },
  components: {
    MyName,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
