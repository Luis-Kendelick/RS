

<template>
  <div>
  <header>
    <navbarComp></navbarComp>
  </header>
  
  
  
  <div>

 

  <div id="t">  <div id="tt"> <a href=""><img id="logoEscritorio" src="/logo2.png" alt="Logo do Escritório" /></a></div> </div>

  

      

  
  <video  id="background-video" autoplay loop muted>
    <source src="/video.mp4" type="video/mp4">
    
    Seu navegador não suporta a reprodução de vídeo.
  </video>
  
  
  </div>
  
  <container id="">

     <carroussel></carroussel>



  </container>
   

      <sobreComp></sobreComp>
      <redeSocialComp></redeSocialComp>

  

  
  </div>
  
  
  </template>


  
  <style scoped>

@import url('https://fonts.googleapis.com/css2?family=Delicious+Handrawn&family=Mrs+Saint+Delafield&family=Rajdhani&family=Spectral:wght@300&display=swap');



.anuncio {
  display: flex;
  overflow: hidden;
  animation: slide 30s linear infinite;
  width: 2100px;


}

.anuncio img {
  width: 1200px;
}

@keyframes slide {
  0% {
    transform: translateX(0%);
  }
  100% {
    transform: translateX(-100%);
  }
}


  @media (max-width: 1000px){    
    #t{
      background-color: brown;
      border-radius: 10%;

    }

    #logoEscritorio{
      width:50vw
    }
  }


  #background-video {
    position: fixed;
    right: 0;
    bottom: 0;
    min-width: 100%;
    min-height: 100%;
    z-index: -1;
    
  }
  

  #t{
      margin-top: 40VW;
      margin-bottom: 40VW;
      padding-left: 10%;
      margin-right: 15%;
      color:aliceblue;
      z-index: 1;
      font-family: 'Spectral', serif;
      font-size: 5vw;
      text-align:center;
 
    }
  
  
  
 
  
  </style>



  <script>

  import navbarComp from '@/components/Header/Navbar.vue'
  import endereçoComp from '@/components/Footer/Endereço.vue'
  import redeSocialComp from '@/components/Footer/RedesSociais.vue'
  import sobreComp from '@/components/Footer/Sobre.vue'
  import Carroussel from './components/Carroussel.vue'
  
  export default {
    components: {
      navbarComp,
      endereçoComp,
      redeSocialComp,
      sobreComp,
      Carroussel,
    }
  }

    
  </script>