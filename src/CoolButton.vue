<template>
  <div>
      <button @click="btnClick">{{ text }}</button>
  </div>
</template>
<script>
export default {
  props: ["text"],
  data: () => {
    return {

    };
  },
  methods: {
    btnClick: () => {
      console.log("Yep! you clicked the button!");
    }
  }
};
</script>
<style lang="scss" scoped>
</style>


