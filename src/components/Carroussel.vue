<template>
  <div class="marquee">
    <img src="/imagem1.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem2.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem3.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem5.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem6.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem7.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem8.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem9.jpeg" style="width: 25vw; height: 60vh;">
    <img src="/imagem10.jpeg" style="width: 25vw; height: 60vh;"> 
    <img src="/imagem4.jpeg" style="width: 25vw; height: 60vh;">

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
  