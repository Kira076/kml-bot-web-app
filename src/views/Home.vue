<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Placeholder />
  </div>
</template>

<script>
// @ is an alias to /src
import Placeholder from "@/components/Placeholder.vue";

export default {
  name: "Home",
  components: {
    Placeholder
  }
};
</script>
