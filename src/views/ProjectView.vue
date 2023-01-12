<template>
    <div class="head animate__animated animate__backInDown">Projects & Skills</div>
    <div class="container">
    <div class="row justify-content-center mx-5">
      <div class="card mx-5 my-4 animate__animated animate__flash" v-for="pro in work" :key="pro" :pro="pro" style="width: 23vw;">
        <div class="imagesByKemp my-3" :style="{ backgroundImage: 'url(' + pro.image + ')' }" alt="..."></div>
        <div class="card-body">
          <h5 class="card-title">{{ pro.name }}</h5>
          <p class="card-text">{{ pro.testimonial }}</p>
        </div>
      </div>
    </div>
</div>
   
</template>

<script>
export default {
    name: 'Project',
  data() {
    return {
      work: [
        {
          name: 'Game Box',
          testimonial: '',
          image: 'https://i.postimg.cc/wjk0gGZk/Screenshot-20230112-162515.png'
        },
        {
          name: 'Calculator',
          testimonial: '',
          image: 'https://i.postimg.cc/3RkBjJRL/Screenshot-20230112-162452.png'
        },
        {
          name: 'First Portfolio',
          testimonial: '',
          image: 'https://i.postimg.cc/W4CrvmNn/Screenshot-20230112-162424.png'
        },
        {
          name: 'Jujutsu Kaisen',
          testimonial: '',
          image: 'https://i.postimg.cc/6QyRgbXq/Screenshot-20230112-162356.png'
        },
        {
          name: 'Sneaker-cartel',
          testimonial: '',
          image: 'https://i.postimg.cc/jjF6j0Xy/Screenshot-20230112-162322.png'
        },
        {
          name: 'First Landpage',
          testimonial: '',
          image: 'https://i.postimg.cc/cH334K6N/Screenshot-20230112-161353.png'
        },

      ]
    }
  }
}
</script>

<style scoped>

</style>