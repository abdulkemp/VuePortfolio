<template>
<div class="head animate__animated animate__backInDown">Projects & Skills</div>
    <div class="container">
    <div class="row justify-content-center mx-2">
      <div class="col-sm-5 mx-2 my-2 animate__animated animate__flash proj" v-for="pro in proj" :key="pro" :pro="pro">
        <h5 class="card-title">{{ pro.name }}</h5>
        <img :src="pro.image" class="imagesByKemp" alt="...">
        <!-- <div class="card-body"> -->
          <p class="card-text">{{ pro.testimonial }}</p>
        </div>
      </div>
    </div>
</template>
  
<script>


export default {
  name: 'Testimonial',
  data() {
    return {
      proj: [
        {
          name: 'Abdul Wahhaab Abrahams',
          testimonial: 'An absolute great guy, hard worker and a goal driven personality. Always takes on the next challenge that comes to him and knows how to communicate and socialise in his surroundings.',
          image: 'https://i.postimg.cc/MHqC38Fw/AbdulW.jpg'
        },
        {
          name: 'Aneeqa Brown',
          testimonial: 'Abdul-Azeez is a highly thought intellectual from my perspective. He is not only hardworking but ambitious to recreate his vision exactly as thought of. He does his work accordingly and always provide a helping hand. He has great communication and leadership skills that a company needs especially his creativity',
          image: 'https://i.postimg.cc/Vkd3VgDJ/Aneeqa.jpg'
        },
        {
          name: 'Mu-eed Brown',
          testimonial: 'Mr. Azeez is a very ambitious person. He will do his best to create whatever he pictures in his mind. He can be very confident, so communication and working with him will be beneficial.',
          image: require('../assets/Mu-eed.jpg')
        },
        {
          name: 'Jake Jansen',
          testimonial: 'Abdul is a very trustworthy individual. Someone you can definitely count on to get the job or task done effectively. He is also very creative and packing ideas. Works really well in groups, communicates well and is open to other peoples ideas.',
          image: require('../assets/Jake.jpg')
        },
        {
          name: 'Nikita Ramawoothar',
          testimonial: 'Azeez is a very creative individual and is always pleasant company to have within the workplace. He is not only helpful but also an exceptional developer that you can always count on to get some ideas and inspiration from.',
          image: require('../assets/nikita.jpg')
        },
        {
          name: 'Karen Bruce',
          testimonial: 'Abdul is a fast learner and dedicated worker. He always seeks more knowledge and encourages himself to gain more experience. He brings a light and motivated energy to the work environment. As an asset to your company, he will ensure that all goals are being achieved.',
          image: require('../assets/karen.jpg')
        },

      ]
    }
  }
}
</script>
<style>
/* .row{
  display: grid;
  justify-content: center;
  align-content: center;
  grid-template-columns: repeat(2, 1fr) / repeat(2. 1fr);
}

.card-body {
  width: 100%;
}

.container {
  position: relative;
  justify-content: center;
  align-items: center;
}

.heading {
  font-size: 10vw;
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
}


.card-text{
  height: 200px;
}

.imagesByKemp {
  width: 100%;
  height: 250px;
  background-repeat: no-repeat;
  background-size: cover;
}
.head{
  font-size: 10vw;
  color: white;
  text-shadow: 0 0 5px, 0 0 25px, 0 0 50px;
} */
.container{
  display: inline-block;
}

.proj{
  max-width: 350px;
  background-color: blue;
  border-radius:10px;
}
.proj img{
  max-width: 95%;
  max-height: 90%;
  margin: 1%;
}

.card-text{
  position: relative;
  color: white;
}

.col{
  position: absolute;
}

/* .my-2 img {
  width: 250px;
  height: 250px;
} */
</style>