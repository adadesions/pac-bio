<template>
  <div class="splash-screen container-fluid">
    <div class="row">
      <loader />
    </div>
  </div>
</template>

<script>
import Loader from "@/components/Loader";

export default {
  name: "SplashScreen",
  components: {
    Loader,
  },
    created() {
      setTimeout(() => {
        this.$router.push("/overview");
      }, 5000);
    },
};
</script>

<style scoped>
.splash-screen {
  display: flex;
  background-image: url("../assets/pac-bio-logo.jpg");
  background-position: center;
  width: 100%;
  height: 100vh;
  background-repeat: no-repeat;
  background-size: cover;
  color: #000;
  justify-content: center;
  align-items: flex-end;
}

.loader {
    margin-bottom: 3em;
}
</style>