<template>
  <div id="app">
    <!-- This will render the current route's component -->
    <!-- <router-link to="/">Go to Home</router-link>
    <router-link to="/about">Go to About</router-link> -->
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>

<style>
/* Add global styles if needed */
</style>
