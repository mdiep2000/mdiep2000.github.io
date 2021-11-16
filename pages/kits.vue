<template>
  <div>
    <app-store-grid :data="kits" />
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
    ...mapGetters(["kits"])
  }
};
</script>

<style lang="scss" scoped>
</style>