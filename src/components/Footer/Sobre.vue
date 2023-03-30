<template>
  <div class="col-12">
    <footer>
      <div class="card" style="width: 100%;">
        <div class="card-body" id="foot">
          <div id="recursos">
            <h2><a href="http://www.google.com">AGENDA DE SHOWS</a></h2>
            <div class="show">
              <div class="date">01 ABR</div>
              <div class="description">SAÍDA SÃO PAULO/SP CHILLI MOB CRUISE</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">05 MAI</div>
              <div class="description">SÃO PAULO/SP AUDIO</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">06 MAI</div>
              <div class="description">RIO DE JANEIRO/RJ VIVO RIO</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">15 MAI</div>
              <div class="description">PARIS/FR NEW MORNING PARIS</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">17 MAI</div>
              <div class="description">BERLIN/DE S036</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">20 MAI</div>
              <div class="description">LONDRES/UK VILLAGE UNDERGROUND</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
            <div class="show">
              <div class="date">21 MAI</div>
              <div class="description">LISBOA/PT CINETEATRO CAPITÓLIO</div>
              <div class="tickets"><a href="http://www.google.com">INGRESSOS</a></div>
            </div>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<style scoped>

h2{
  font-size: 3vw;
  color: #ff3831;
}
.show{
  display: flex;
  
}

#recursos {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  gap: 2rem;
  margin-top: 3.5rem;
  margin-bottom: 3.5rem;  
  font-family: 'Spectral', serif;
  text-align: center;
}

#recursos .evento {
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 25%;
}

#recursos .evento .date {
  font-size: 2.5vw;
  font-weight: bold;
  margin-bottom: 1rem;
  margin-right: 10px;
}

#recursos .evento .description {
  font-size: 2vw;
  margin-bottom: 1rem;
}

#recursos .evento .tickets {
  font-size: 2vw;
  text-decoration: none;
  color: black;
}

.date{
  font-size: 2vw;
  margin-right: 2vw;
  color: #ff3831;
}


.description{

  font-size: 2vw;
  margin-right: 2vw;

}
.tickets{

  font-size: 2vw;
  
}

/* -----------------------------------------
 */

 @media (max-width: 1000px){    

  .date{
  font-size: 4vw;
  margin-right: 2vw;
  color: #ff3831;
}


.description{

  font-size: 4vw;
  margin-right: 2vw;

}
.tickets{

  font-size: 4vw;
  
}

}

</style>

