<template>
    <div class="head animate__animated animate__backInDown">Projects & Skills</div>
    <div class="container">
    <div class="row justify-content-center mx-2">
      <div class="col-sm-5 mx-2 my-2 proj " v-for="pro in work" :key="pro" :pro="pro">
        <img :src="pro.image" class="imagesByKemp" alt="...">
        <h5 class="card-title">{{ pro.name }}</h5>
        <!-- <div class="card-body"> -->
          <div class="but">
         <a :href="pro.github" target="_blank"> <button class="butt">GitHub</button></a>
         <a :href="pro.netlify" target="_blank"> <button class="butto">Go Live</button></a>
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
          github: 'https://github.com/abdulkemp/project.git',
          netlify: 'https://project1-e-commerce.netlify.app/',
          image: 'https://i.postimg.cc/cLydgrb4/Screenshot-20230112-162515.png'
        },
        {
          name: 'Calculator',
          github: 'https://github.com/abdulkemp/calculatorJs.git',
          netlify: 'https://calculatorjsnew1.netlify.app/',
          image: 'https://i.postimg.cc/3RkBjJRL/Screenshot-20230112-162452.png'
        },
        {
          name: 'First Portfolio',
          github: 'https://github.com/abdulkemp/MyPortfolio.git',
          netlify: 'https://abdul-azeez-kemp.netlify.app/',
          image: 'https://i.postimg.cc/W4CrvmNn/Screenshot-20230112-162424.png'
        },
        {
          name: 'Jujutsu Kaisen',
          github: 'https://github.com/abdulkemp/testimonial.git',
          netlify: 'https://jujutsu.netlify.app/',
          image: 'https://i.postimg.cc/6QyRgbXq/Screenshot-20230112-162356.png'
        },
        {
          name: 'Sneaker-cartel',
          github: 'https://github.com/abdulkemp/Sneaker_Cartel.git',
          netlify: 'https://sneaker-cartel.netlify.app/',
          image: 'https://i.postimg.cc/jjF6j0Xy/Screenshot-20230112-162322.png'
        },
        {
          name: 'First Landpage',
          github: 'https://github.com/abdulkemp/new-landpage.git',
          netlify: 'https://newlandpage.netlify.app/',
          image: 'https://i.postimg.cc/cH334K6N/Screenshot-20230112-161353.png'
        },

      ]
    }
  }
}
</script>

<style scoped>
.container{
  display: inline-block;
}

.proj{
  height: 40vh;
  max-width: 350px;
  background: linear-gradient(
              40deg,
              rgb(0, 0, 0),
               rgb(28, 28, 28),
               grey,
               white
  );
  background-size: 100% 100%;
  border-radius:10px;
}
.proj img{
  max-width: 95%;
  height: 150px;
  margin-top: 10%;
  border-top-left-radius: 7px;
  border-top-right-radius: 7px;
}
.but{
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 10px;
  gap: 10px;
}
.butt{
  border-radius: 7px;
  border: 0px solid transparent;
  color: white;
  background-color: rgb(0, 0, 0);
}
.butto{
  border-radius: 7px;
  border: 0px solid transparent;
  color: black;
  background-color: rgb(255, 89, 0);
}

</style>