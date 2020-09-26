<template>
  <div>
    <Header />
    <header>USERS SECTION</header>
    <!-- Nuxt /> place where different plages should be loaded in -->
    <Nuxt />
  </div>
</template>

<script>
import Header from "@/components/Header.vue";
export default {
  components: {
    Header,
  },
};
</script>  