<template>
  <q-layout view="hHh lpR fFf">
    <div class="center row">
      <div class="navbar col-2 column justify-center">
        <div class="btn-group">
          <q-btn-group push></q-btn-group>
        </div>
      </div>
      <div class="pages col">
        <h2>About</h2>
      </div>
    </div>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  data() {
    return {};
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
</style>