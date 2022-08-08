<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <header class="shadow-sm shadow-green-100">
    <div
      class="flex justify-between items-center container mx-auto py-4"
    >
      <div class="logo">
        <h1
          class="text-2xl animate__animated animate__rubberBand animate__delay-2s animate__infinite"
        >
          Roman <span>Sheikh</span>
        </h1>
      </div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/portfolio">Portfolio</RouterLink>
        <RouterLink to="/contact">Contact</RouterLink>
      </nav>
    </div>
  </header>
</template>


<style scoped>
.logo h1{
  color: hsla(160, 100%, 37%, 1);
  font-family: Oleo Script Swash Caps;
}

nav a.router-link-exact-active {
  color: hsla(160, 100%, 37%, 1);
}

nav a:hover{
  color: hsla(160, 100%, 37%, 1);
  background-color: hsla(160, 100%, 37%, 0.2);
}

nav a {
  display: inline-block;
  padding: 0.3rem 1rem;
  color: #ddd;
  font-size: 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}
</style>
