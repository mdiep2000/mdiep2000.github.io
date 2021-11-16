<template>
  <div>
    <app-store-grid :data="seeds" />
  </div>
</template>

<script>
import { mapGetters } from "vuex";
import AppStoreGrid from "~/components/AppStoreGrid.vue";

export default {
  components: {
    AppStoreGrid
  },
  computed: {
    ...mapGetters(["seeds"])
  }
};
</script>

<style lang="scss" scoped>
</style>