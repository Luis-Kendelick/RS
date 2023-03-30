<template>
  <!-- <div class="marquee">
    <img v-for="image in images" :key="image" :src="require(`../assets/${image}`)" style="width: 25vw; height: 60vh;">
  </div> -->
</template>

<script>
export default {
  name: 'Carroussel',
  data() {
    return {
      images: [
        'WhatsApp Image 2023-03-29 at 14.58.03 (1).jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.03 (2).jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.04 (1).jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.04 (2).jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.04.jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.03.jpeg',
        'WhatsApp Image 2023-03-29 at 16.06.09.jpeg',
        'WhatsApp Image 2023-03-29 at 16.06.10 (1).jpeg',
        'WhatsApp Image 2023-03-29 at 16.06.10.jpeg',
        'WhatsApp Image 2023-03-29 at 14.58.02.jpeg'
      ]
    }
  }
}
</script>

<style scoped>
.marquee {
  width: 100%;
  height: 70vh;
  overflow: hidden;
  white-space: nowrap;
}

.marquee img {
  display: inline-block;
  width: 20vw;
  height: 550px;
  margin-right: 10px;
  animation: marquee 90s linear infinite;
  border: 15px solid white;
  border-radius: 20px;
}

@keyframes marquee {
  0% {
    transform: translateX(-25vw);
  }
  100% {
    transform: translateX(-175vw);
  }
}
</style>
