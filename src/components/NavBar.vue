<template>
    <div class="collapse" id="navbarToggleExternalContent">
  <div class="bg p-4">
    <span class="text-muted">
    <router-link to="/">Home</router-link> |
    <router-link to="/About">About</router-link> |
    <router-link to="/ResumeView">Resume</router-link> |
    <router-link to="/ProjectView">Projects</router-link> |
    <router-link to="/Testimonial">Testimonial</router-link> |
    <router-link to="/Contact">Contact</router-link> 
    </span>
  </div>
</div>
<nav class="navbar navbar-dark">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
  </div>
</nav>
<div class="di"></div>

</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style>
.collapse{
  position: relative;
  z-index: 2;
}
.text-muted a:hover{
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
}

.navbar{
  z-index: 2;
  position: relative;
}
</style>