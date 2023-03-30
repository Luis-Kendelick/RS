<template>
  <div class="marquee">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.02.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03 (2).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04 (2).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.09.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.10 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.10.jpeg" style="width: 25vw; height: 60vh;">


    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.02.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03 (2).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04 (2).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.04.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 14.58.03.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.09.jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.10 (1).jpeg" style="width: 25vw; height: 60vh;">
    <img src="src\assets\WhatsApp Image 2023-03-29 at 16.06.10.jpeg" style="width: 25vw; height: 60vh;">
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
  