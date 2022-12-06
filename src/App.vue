<template>
  <div>
    <h1>{{ welcome }}</h1>
  </div>
</template>

<script>
export default {
  data () {
    return {
      welcome: "Welcome Boolean"
    };
  }
};
</script>

<style lang="scss">
@use "./styles/general.scss";

</style>
