<template>
  <div id="app">
    <ExampleOne/>
  </div>
</template>

<script>
import ExampleOne from "./components/example-one";
import 'bootstrap/dist/css/bootstrap.min.css'

export default {
  name: "App",
  components: {
    ExampleOne
  }
};
</script>