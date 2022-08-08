<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/more">More</RouterLink>
      </nav>
    </div>
  </header>
</template>


<style scoped>
nav {
  width: 100%;
  font-size: 12px;
  text-align: right;
  margin-top: 1rem;
}

nav a.router-link-exact-active {
  color: hsla(160, 100%, 37%, 1);
}

nav a:hover{
  color: hsla(160, 100%, 37%, 1);
}

nav a {
  display: inline-block;
  
  padding: 0 1rem;
  color: var(--color-text);
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}
</style>
