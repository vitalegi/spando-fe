<template>
  <div>
    <h1>This is an spando page</h1>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "spando-main",
  data() {
    return {
      pending: 10
    };
  },
  computed: {
    dialog(): boolean {
      return this.pending > 0;
    }
  }
});
</script>

<style scoped></style>
