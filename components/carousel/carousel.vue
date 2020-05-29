<template>
  <div>
    <b-carousel id="carousel-1" :interval="3000" indicators>
      <b-carousel-slide>
        <template v-slot:img>
          <img class="img" src="../../assets/imgs/img1.jpeg" />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template v-slot:img>
          <img class="img" src="../../assets/imgs/img2.jpeg" />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template v-slot:img>
          <img class="img" src="../../assets/imgs/img3.jpeg" />
        </template>
      </b-carousel-slide>
      <b-carousel-slide>
        <template v-slot:img>
          <img class="img" src="../../assets/imgs/img4.jpeg" />
        </template>
      </b-carousel-slide>
    </b-carousel>
  </div>
</template>

<style>
.img {
  object-fit: cover;
  width: 100vw;
  height: 300px;
}
</style>