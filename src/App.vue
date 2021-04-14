<template>
  <div id="app">
    <!-- Inserting the header, body and footer components into the HTML file so that it can be used to style the tags and show up on the page -->
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
    <!-- Adding a link to use the Open Sans font -->
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans&display=swap" rel="stylesheet">
  </div>
</template>

<script>
// Importing the header, body and footer components
import PageHeader from "./components/PageHeader.vue";
import PageBody from "./components/PageBody.vue";
import PageFooter from "./components/PageFooter.vue";

// Registering the header, body and footer components
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