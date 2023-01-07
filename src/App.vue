<template>
  <div class="px-5">
    <div class="d-flex justify-content-center my-4">
      <img src="./assets/logo.svg" alt="logo" height="100" width="175" />
    </div>
    <div class="d-flex justify-content-center">
      <div class="d-md-flex">
      <AirQuality />
      <TemperatureList />
      <AudioList />
      </div>
    </div>
    <div class="d-flex justify-content-center"> 
      <div class="d-md-flex">
      <DisPlays />
      <LightingList />
      </div>
    </div>
  </div>
</template>

<script>
import AirQuality from "./components/AirQuality.vue";
import TemperatureList from "./components/TemperatureList.vue";
import AudioList from "./components/AudioList.vue";
import DisPlays from "./components/DisPlays.vue";
import LightingList from "./components/LightingList.vue";

export default {
  name: "App",
  components: {
    AirQuality,
    TemperatureList,
    AudioList,
    DisPlays,
    LightingList,
  },
};
</script>

<style>
@import "./assets/app.css";
</style>
