<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header >
    <div class="wrapper">
    

      <nav class = "sticky">
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>
header {
  line-height: 1.5;
  height: 50px;
  max-height: 100vh;
  position: relative;
}


nav {
width: 100%;
font-size: 10px;
text-align: center;
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }

  nav {
  position: fixed;  /* Positions the nav */
  top: 1rem;          
  right: 1rem;         
  z-index: 2;;
  text-align: right;
  margin-right: 0;      /* Remove left margin to avoid shifting */
  font-size: 0.7rem;

}

}
</style>
