<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="현재 Vue.js 로 App을 서비스 중입니다!!" />
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  }, //,
  // mounted() {
  //   if (window.kakao && window.kakao.maps) {
  //     this.initMap();
  //   } else {
  //     const script = document.createElement("script");
  //     /* global kakao */
  //     script.onload = () => kakao.maps.load(this.initMap);
  //     script.src =
  //       "http://dapi.kakao.com/v2/maps/sdk.js?autoload=false&appkey=97ef3485b87cdb41adf506a8c42c308d";
  //     document.head.appendChild(script);
  //   }
  // },
  // methods: {
  //   initMap() {
  //     var mapContainer = document.getElementById("map"), // 지도를 표시할 div
  //       mapOption = {
  //         center: new kakao.maps.LatLng(37.564343, 126.947613), // 지도의 중심좌표
  //         level: 3, // 지도의 확대 레벨
  //       };

  //     var map = new kakao.maps.Map(mapContainer, mapOption);
  //   },
  // },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
