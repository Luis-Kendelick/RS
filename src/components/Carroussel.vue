<template>
  <div class="marquee">
    <img src="../assets/imagem1.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem2.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem3.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem4.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem5.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem6.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem7.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem8.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem9.jpeg" style="width: 25vw; height: 60vh;">
    <img src="../assets/imagem10.jpeg" style="width: 25vw; height: 60vh;">


  </div>
  </template>
  
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
    border: 2px solid white;
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
  