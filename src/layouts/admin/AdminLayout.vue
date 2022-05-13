<template>
  <div>
    <Header />
    <Sidenav />
  </div>
</template>
<script>
import Header from "@/views/admin/Header.vue";
import Sidenav from "@/views/admin/Sidenav.vue";

export default {
  components: {
    Header,
    Sidenav,
  },
};
</script>