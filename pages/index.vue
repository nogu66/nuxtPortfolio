<script lang="ts">
import Vue from "vue";
import Header from "@/components/Header.vue";
import Footer from "@/components/Footer.vue";
import Hero from "@/components/Hero.vue";
import Works from "@/components/Works.vue";

export default Vue.extend({
  name: "IndexPage",
});
</script>

<template>
  <div>
    <Header />
    <Hero />
    <Works />
    <Footer />
  </div>
</template>
