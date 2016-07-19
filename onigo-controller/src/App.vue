<template>
  <inactive-screen :message="inactiveMessage"></inactive-screen>
</template>

<script>
import InactiveScreen from "./components/InactiveScreen";

export default {
  data () {
    return {
      inactiveMessage: "This shows when the game is inactive."
    };
  },
  components: {
    InactiveScreen
  }
};
</script>

<style>
html {
  height: 100%;
}

body {
  background-color: #34495e;
  color: white;
  margin: 0px;
  height: 100%;
  display: flex;
  flex-direction: column;
  overflow: hidden;
}
</style>
