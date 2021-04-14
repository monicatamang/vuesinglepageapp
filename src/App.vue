<template>
  <div id="app">
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
  </div>
</template>

<script>
// Importing the header, body and footer components into the home page
import PageHeader from "./components/PageHeader.vue";
import PageBody from "./components/PageBody.vue";
import PageFooter from "./components/PageFooter.vue";

// Registering the header, body and footer components into the home page
export default {
  name: 'App',
  components: {
    PageHeader,
    PageBody,
    PageFooter
  }
}
</script>

<style>
#app {
  font-family: 'Open Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

* {
  margin: 0;
  padding: 0;
}
</style>