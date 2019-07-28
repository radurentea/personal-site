<template>
  <div class="navbar col-2 column justify-center">
    <div class="btn-group">
      <button>About</button>
      <button>Project 1</button>
      <button>Project 2</button>
      <button>Project 3</button>
      <button>Working</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {};
  }
};
</script>

<style>
.btn-group button {
  background-color: #4caf50; /* Green background */
  border: 1px solid green; /* Green border */
  color: white; /* White text */
  padding: 10px 24px; /* Some padding */
  cursor: pointer; /* Pointer/hand icon */
  width: 100%; /* Set a width if needed */
  display: block; /* Make the buttons appear below each other */
}
.btn-group button:hover {
  background: #4cafa0;
}
</style>
