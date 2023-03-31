<template>
 
        <nav id="navbar" class="navbar navbar-expand-lg" style="background-color: white; width: 100%;" >
                <a href=""><img id="logoEscritorio" src="public\logo.png" alt="Logo do Escritório" /></a>
                
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>

                
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" id="home" href="../index.html">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.instagram.com/suyama.adv/">Agenda</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.linkedin.com/in/rafael-moreira-suyama-0043bb189/">Loja</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.linkedin.com/in/rafael-moreira-suyama-0043bb189/">Vídeos</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.linkedin.com/in/rafael-moreira-suyama-0043bb189/">Ouça agora</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="https://www.linkedin.com/in/rafael-moreira-suyama-0043bb189/">Fotos</a>
                        </li>
                        <li class="nav-item">
                        
                        <router-link to="/teste" class="nav-link">Contato</router-link>

                        </li> 
                    </ul>
                <div class="nav-item dropdown" id="redeSociais">
                    
                       <a  href="https://www.instagram.com/suyama.adv/"><img id="ico2" src="public\instagram.svg" alt="Insta" /> </a>
                       <a  href="https://www.linkedin.com/in/rafael-moreira-suyama-0043bb189/"><img id="ico2" src="public\youtube.svg" alt="Youtube" /> </a>
                       <a  href="https://wa.me/5513996267989"><img id="ico2" src="public\whatsapp.svg" alt="Whats" /></a>
                       <a  href="https://wa.me/5513996267989"><img id="ico2" src="public\facebook.svg" alt="Whats" />   </a>
                    

                </div> 
                </div>
          
        </nav>

  </template>

  <style scoped>


/* 
------------------------------- */

.navbar-nav > a:not(:last-child) {
  margin-right: 1vw;
}

#redeSociais > a:not(:last-child) {
  margin-right: 1vw;
}

.navbar-nav{
    display:flex;
    flex-direction:row;
    justify-content: space-between;
}

#home{
    color:#ff3831;
}

#navbar{  padding: 1vw;
    box-shadow: 11px 13px 24px 0px rgba(0,0,0,0.75);
}
  
  #logoEscritorio{
        width: 10vw;
        margin-left: 2vw;
        margin-right: 4vw;
        

  }

  a{
    font-size: 1.5vw;
    font-family: 'Spectral', serif;

  }

  #ico2{

width:3vw;
padding-right: 0.3vw;
}


/* -----------------------------------------
 */

@media (max-width: 1000px){    


    #logoEscritorio{
        width: 20vw;
        margin-left: 2vw;
        margin-right: 4vw;
        

  }

  a{
    font-size: 3vw;
    font-family: 'Spectral', serif;

  }

  #ico2{

    width:5vw;
    padding-right: 0.3vw;
  }

  #redeSociais{
    display: flex;
    justify-content: flex-end;
  }
}

  </style>
  
