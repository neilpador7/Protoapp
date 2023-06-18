<script setup lang="ts">
import AppBar from "./components/AppBar.vue";
import Home from "./components/Home.vue";
</script>

<template>
  <div class="container">
    <div class="header">
      <AppBar />
    </div>
    <div class="body">
      <Home />
    </div>
  </div>
</template>

<style>
@import "./assets/base.css";

/* Common styles for different screen sizes */
h1 {
  margin: 0;
  font-size: 4rem;
  font-weight: bold;
}

h2 {
  margin: 0;
  font-size: 2rem;
  font-weight: 100;
}

h3 {
  margin: 0;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

a,
.black {
  text-decoration: none;
  color: rgb(0, 0, 0);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

/* Responsive styles */
@media (min-width: 0) {
  body {
    background-image: url("./assets/bg-leaves.svg"),
      url("./assets/bg-decals.svg"),
      url("./assets/bg-decals2.svg"),
      url("./assets/bg-decals3.svg");
    background-position: top right, -5rem 25rem , 75rem 220rem, bottom;
    background-repeat: no-repeat, no-repeat, no-repeat, no-repeat;
    background-size: 80%, contain, auto, contain;
    padding: 0;
  }

  #app {
    margin: 0;
    padding: 0.5rem;
  }

  header.wrapper {
    padding: 0.5rem;
  }

  .logo {
    margin-bottom: 1rem;
  }

  .container {
    padding: 0 1rem;
  }

  .body {
    margin-left: 0;
  }
}

@media (min-width: 400px) {
  body {
    display: flex;
    place-items: center;
  }

  #app {
    display: flex;
    place-items: center;
    max-width: 2000px;
    width: 100%;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 0.5rem;
    flex-grow: 1;
    flex-shrink: 1;
    box-sizing: border-box;
    margin: 0;
  }

  header {
    display: flex;
    place-items: flex-start;
    padding-right: calc(var(--section-gap) / 2);
  }

  header.wrapper {
    padding: 0.5rem;
  }

  .logo {
    margin: 0 2rem 0 0;
  }
 
}
</style>
