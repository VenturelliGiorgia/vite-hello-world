<script>
import AppTitle from "./components/AppTitle.vue";
export default {
  components: { AppTitle },
  data() {
    return {
      messaggio: "Hello Vite"
    };
  },
  methods: {
    fetchData() {
    }
  }
};
</script>

<template>
  <div class="container">
    <AppTitle></AppTitle>
  </div>
</template>