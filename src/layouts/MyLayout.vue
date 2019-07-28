<template>
  <q-layout view="hHh lpR fFf">
    <div class="center row">
      <Navbar />
      <div class="pages col">
        <h2 class="text-center">About</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Dolor, rerum. Quibusdam, rerum! Corrupti iste recusandae maiores, harum culpa doloribus blanditiis. Dolor voluptas consequuntur earum autem. Soluta vero saepe ea ducimus!</p>
      </div>
    </div>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
import Navbar from "../components/Navbar";

export default {
  data() {
    return {};
  },
  components: {
    Navbar
  }
};
</script>

<style>
.center {
  position: fixed;
  background: #fff;
  width: 50em;
  top: 50%;
  left: 50%;
  height: 26em;
  margin-top: -13em; /*set to a negative number 1/2 of your height*/
  margin-left: -25em; /*set to a negative number 1/2 of your width*/
}

.pages {
  margin: 0 auto;
  padding: 0 1em;
}
</style>