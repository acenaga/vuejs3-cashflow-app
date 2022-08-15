<template>
  <layout-cash>
    <template #header>
      <header-cash></header-cash>
    </template>
  </layout-cash>
</template>

<script>
import LayoutCash from "./LayoutCash.vue";
import HeaderCash from "./HeaderCash.vue";

export default {
  components: {
    LayoutCash,
    HeaderCash
  }
};
</script>
