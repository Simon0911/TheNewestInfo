<template>
  <div class="home">
    <TheNewestInfo />
  </div>
</template>

<script>
// @ is an alias to /src
import TheNewestInfo from "@/components/TheNewestInfo.vue";

export default {
  name: "Home",
  components: {
    TheNewestInfo,
  },
};
</script>
