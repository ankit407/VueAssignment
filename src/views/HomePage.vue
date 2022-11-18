<template>
  <div>
    <NavBarView />
    <HomePageView />
    <AboutView />
  </div>
</template>
<script>
import NavBarView from "../components/NavBar";
import HomePageView from "../components/HomeView.vue";
import AboutView from "../components/HomeAbout.vue";
export default {
  name: "HomePage",
  components: {
    NavBarView,
    HomePageView,
    AboutView,
  },
};
</script>
