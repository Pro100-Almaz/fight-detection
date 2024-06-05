<template>
    <div>
      <h1>Live Video Stream</h1>
      <img :src="videoUrl" alt="Live Video Stream">
    </div>
  </template>
  <script>
  export default {
    data() {
      return {
        videoUrl: 'http://192.168.0.123:8080/video_feed'
      };
    }
  };
  </script>
  
  <style scoped>
  img {
    width: 60%;
    height: auto;
    border: 1px solid #ddd;
    border-radius: 4px;
    padding: 5px;
  }
  </style>
  