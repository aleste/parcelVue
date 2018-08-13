<template>
  <div id="app">
    <h4>{{ appName }}</h4>
    <cool-button text="Button #1"></cool-button>
    <cool-button text="Button #2"></cool-button>
  </div>
</template>

<script>
import CoolButton from "./CoolButton.vue";

export default {
  name: "app",
  data() {
    return {
      appName: "A Parcel & Vue test project."
    };
  },
  components: {
    CoolButton
  }
};
</script>

<style lang="scss" scoped>
h4 {
  background-color: rgb(79, 77, 235);
  color: white;
  padding: 3px;
}
</style>
