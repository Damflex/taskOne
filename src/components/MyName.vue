<template>
  <div class="center">
    <p>{{myName}}</p>
  </div>
</template>

<script>
export default {
  name: "MyNameComponent",
  props: {
    myName: {
      type: String,
      default: "Nwulu Uchechukwu",
    },
  },
};
</script>

<style lang="scss" scoped>
.center {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 50vh;
}
p {
  color: red;
}
</style>
