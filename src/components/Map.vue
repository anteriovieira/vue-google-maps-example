<template>
  <div class="map-container">
    <gmap-map :center="{lat:1.38, lng:103.8}" :zoom="12">
      <gmap-marker :position="{lat:1.38, lng:103.8}">
      </gmap-marker>
      <gmap-info-window :position="{lat:1.38, lng:103.8}">
        Hello world!
      </gmap-info-window>
    </gmap-map>
  </div>
</template>

<script>
  export default {
    name: 'map'
  }
</script>

<style>
  .map-container, .vue-map-container {
    display: flex;
    width: 100%;
  }
</style>