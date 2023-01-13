<template>
  <div class="ho">
    <NavBar />
    <router-view />
     <!-- <ul class="animation">
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
  </ul> -->
  </div>

 
  
  <Footer />
</template>

<script>
import NavBar from './components/NavBar.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: { NavBar, Footer },
}

</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  overflow: hidden;
}

nav {
  padding: 10px;
}

nav a {
  font-weight: bold;
  color: black;
  text-decoration: none;
}

nav a.router-link-exact-active {
  color: white;
}

.ho {
  min-height: 100vh;
  
}
/* .animation{
  position: absolute;
  top: 0%;
  right: 0%;
  width: 100%;
  height: 100%;
  z-index: 1;
}
.animation li{
  position: absolute;
  display: block;
  background: rgba(227, 232, 194, 0.107);

  list-style: none;
  animation: animate 15s linear infinite;
  width: 30px;
  height: 30px;
  bottom: -150px;
}
.animation li:nth-child(1){
  right: 16.7%;
  height: 100px;
  width: 100px;
  animation-delay: 3s;
}
.animation li:nth-child(2){
  right: 25%;
  height: 35px;
  width: 35px;
  animation-delay: 2s;
}
.animation li:nth-child(3){
right: 50%;
  height: 15px;
  width: 15px;
  animation-delay: 1s;
}
.animation li:nth-child(4){
  right: 80%;
  height: 55px;
  width: 55px;
  animation-delay: 5s;
}
.animation li:nth-child(5){
  right: 5%;
  height: 20px;
  width: 20px;
  animation-delay: 4;
}
.animation li:nth-child(6){
  right: 99%;
  height: 38px;
  width: 38px;
  animation-delay: 3s;
}
.animation li:nth-child(7){
  right: 60%;
  height: 63px;
  width: 63px;
  animation-delay: 0s;
}
.animation li:nth-child(8){
  right: 36%;
  height: 5px;
  width: 5px;
  animation-delay: 5s;
}
.animation li:nth-child(9){
  right: 40%;
  height: 33px;
  width: 33px;
  animation-delay: 3s;
}
.animation li:nth-child(10){
  right: 58%;
  height: 14px;
  width: 14px;
  animation-delay: 3s;
}
.animation li:nth-child(11){
  right: 69.5%;
  height: 40px;
  width: 40px;
  animation-delay: 4s;
}
.animation li:nth-child(12){
  right: 12%;
  height: 40px;
  width: 40px;
  animation-delay: 4s;
}
.animation li:nth-child(13){
  right: 59%;
  height: 28px;
  width: 28px;
  animation-delay: 2s;
}
.animation li:nth-child(14){
  right: 30%;
  height: 28px;
  width: 28px;
  animation-delay: 4s;
}
.animation li:nth-child(15){
  right: 87%;
  height: 20px;
  width: 20px;
  animation-delay: 5s;
}
@keyframes animate {
  0%{
    transform: translateY(0) rotate(0deg);
    opacity: 1;
    border-radius: 0;
  }
  100%{
    transform: translateY(-1000px) rotate(360deg);
    opacity: 0;
  }
} */
</style>
