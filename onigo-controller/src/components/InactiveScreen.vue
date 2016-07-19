<template>
  <div id="inactive-screen">
    <div id="inactive-inner">
      {{ message }}
    </div>
  </div>
</template>

<script>
export default {
  props: {
    message: String
  }
};
</script>

<style>
#inactive-screen {
  position: fixed;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: 5;
  background-color: rgba(0, 0, 0, 0.6);
}

#inactive-inner {
  width: 100%;
  text-align: center;
  background-color: black;
  color: white;
  position: absolute;
  top: 50%;
  padding: 20px 0;
  transform: translateY(-50%);
}
</style>
