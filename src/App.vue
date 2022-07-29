<template>
  <div id="app">
    <!-- <nav>
      <router-link to="/">HOME</router-link> |
      <router-link to="/about">ABOUT</router-link> |
      <router-link to="/about">CONTACT</router-link>
    </nav> -->
    <div class="Banner-section">
      <BannerDetails />
    </div>
    <div class="Engenerng-section">
      <EngineeringDetails />
    </div>
    <div class="Leadership-section">
      <LeaderSkillsDetails />
    </div>
    <router-view />
  </div>
</template>
<script>
import BannerDetails from "@/components/BannerDetails.vue";
import EngineeringDetails from "./components/EngineeringDetails.vue";
import LeaderSkillsDetails from "./components/LeaderSkillsDetails.vue";

export default {
  components: {
    BannerDetails,
    EngineeringDetails,
    LeaderSkillsDetails,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
