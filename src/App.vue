<template>
  <Navbar />
  <!-- <div class="flex text-center">
    <div class="m-auto">
      <h4>Your position</h4>
      Latitude: {{ currPos.lat.toFixed(2) }},Longitude:
      {{ currPos.lng.toFixed(2) }}
    </div>
  </div> -->
</template>

<script setup>
import { computed } from "vue";
import { useGeo } from "./useGeo";
import Gmap from "./components/GMap.vue";
import Navbar from "./components/layout/Navbar.vue";

// export default {
//   name: "App",
//   setup() {
//     const { coords } = useGeo();
//     const currPos = computed(() => ({
//       lat: coords.value.latitude,
//       lng: coords.value.longitude,
//     }));
//     return { currPos };
//   },
// };
// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
</style>