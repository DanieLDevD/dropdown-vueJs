<template>
  <div id="app">
    <header>
      <NavbarItem />
    </header>
  </div>
</template>

<script>
import NavbarItem from "./components/Navbar.vue";

export default {
  name: "App",
  components: {
    NavbarItem,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "montserat", sans-serif;
}

header {
  width: 100vw;
  background-color: #222;
  padding: 15px;
}
</style>
