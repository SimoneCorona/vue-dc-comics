<template>
  <div id="app">
    <!-- Header -->
    <MyAppHeader />
    <!-- Main -->
    <main>
      <div class="container">
        -->Content goes here
      </div>
    </main>
    <!-- Jumbotron -->
    <MyAppJumbotron />
    <!-- Footer -->
  </div>
</template>

<script>
import MyAppHeader from "./components/MyAppHeader.vue";
import MyAppJumbotron from "./components/MyAppJumbotron.vue";


export default {
  name: 'App',
  components: {
    MyAppHeader,
    MyAppJumbotron,
}
}
</script>

<style lang="scss">
@import "./style/common.scss";

main{
  height: 80px;
  background-color: black;
  color: white;
}


</style>
