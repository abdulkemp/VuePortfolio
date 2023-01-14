<template>
  <div class="head animate__animated animate__backInDown">About Me</div>
  <div class="container">
    <div class="row justify-content-center mx-2">
      <div class="col-sm-5 mx-2 my-2 animate__animated animate__flash proj">
        <img src="https://i.postimg.cc/wBvZDWrt/pfp.jpg" alt="...">
        <h5 class="card-title">Developer & Designer</h5>
        <p class="card-text">I, Abdul-Azeez Kemp, am a hardworking individual that is also constantly wanting to learn
          new things. What
          got
          me into wanting to start a career in IT was that how things are made and that always fascinates me and I
          would
          like to create things myself.</p>
        <router-link to="/Contact" > <button type="button"> Let's Talk</button></router-link>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: 'About',
}
</script>

<style scoped>

.card-text {
  position: relative;
  color: white;
}
.card-title {
  color: red;
  font-size: 40px;
} 

.container button {
  background-color:orangered;
  border-radius: 20px;
  color: black;
}

.container button:hover {
  background-color: black;
  color: white;
} 


.container {
  display: inline-block;
}

.proj img {
  max-width: 95%;
  max-height: 90%;
  margin: 1%;
}

.head {
  font-size: 8vw;
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
}
</style>