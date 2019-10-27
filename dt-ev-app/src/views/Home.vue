<template>
  <div style="height: 100%">
    <ParkingSpots></ParkingSpots>
  </div>
 <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>-->
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";
// import TheHeader from '../components/TheHeader';
import ParkingSpots from '../components/ParkingSpots';

export default {
  name: "home",
  components: {
    // HelloWorld,
    // TheHeader,
    ParkingSpots
  }
};
</script>
