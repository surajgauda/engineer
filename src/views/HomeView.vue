<template>
  <div class="home">
    <HelloWorld />
    <div>
      <BannerDetails />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import BannerDetails from "@/components/BannerDetails.vue";

export default {
  name: "HomeView",
  components: {
    HelloWorld,
    BannerDetails,
  },
};
</script>
