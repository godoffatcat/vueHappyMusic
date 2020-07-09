<template>
  <div>
    <TitleBar />
    <Banner />
    <h1>hey you!</h1>
  </div>
</template>

<script>
  import Banner from "./banner.vue";
  import TitleBar from "../littleComponents/titleBar.vue"

  export default {
    name: "Index",
    components: {
      Banner,
      TitleBar,
    }
  };
</script>

<style></style>
