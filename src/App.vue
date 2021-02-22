<template>
  <div id="app">
    <navbar />
    <main class="container mx-auto">
      <router-view />
    </main>
  </div>
</template>

<script>
import Navbar from "@/components/Navbar";

export default {
  components: { Navbar }
};
</script>

<style lang="scss"></style>
