<template>
  <div id="app">
    <HeaderBar />
    <div class="main-section columns">
      <main class="column">
        <Heroes />
      </main>
    </div>
  </div>
</template>
  
<script>
  import HeaderBar from "@/components/header-bar";
  import Heroes from "@/components/heroes-section";

  export default {
    name: "App",
    components: { HeaderBar, Heroes },
  };
</script>
  
<style lang="scss">
  @import "@/design/index.scss";
  @import url("https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap");
</style>
  