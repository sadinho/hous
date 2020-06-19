<template>
  <div class="w3-col ">
    <button class='w3-btn w3-green' @click="mudandoCor('verde')">verde</button>
    <button class='w3-btn w3-blue' @click="mudandoCor('azul')">azul</button>

    <div class="w3-col cabecalho w3-center" :style="mudarCor()">
      <label class="titulo w3-col">{{titulo}}</label>
      <label class="sub-titulo w3-col">{{sub_titulo}}</label>
    </div>

    <div class="w3-col bloco-corpo">
      <div class="w3-col l6 w3-btn principal">
        <div 
          id="texto-principal"
          class="w3-left-align w3-col titulo-card">
          {{titulo_card1}}
        </div>

         <div 
          id="sub-texto-principal"
          class="w3-col w3-left-align titulo-card">
          {{titulo_card2}}
        </div>

        <div
          id="ano" 
          class="w3-col w3-left-align titulo-card">
          {{ano}}
        </div>

        <div 
          id="texto-principal-inf"
          class="w3-col s2 m2 l2 w3-left-align titulo-card">
          <span class="w3-col">
            Lorem Ipsum available, <br/>
            but the <br/>
            suffered alterationsome <br/>
            form humour, <br/>
            or randomised words
          </span>
          <div class='w3-col w3-margin-top'>
            <i class="fa fa-linkedin w3-btn" aria-hidden="true"></i>
           
            <i class="fa fa-pinterest w3-btn" aria-hidden="true"></i>
           
            <i class="fa fa-twitter w3-btn" aria-hidden="true"></i>
           
            <i class="fa fa-facebook w3-btn" aria-hidden="true"></i>
          </div>
        </div>
        <img 
          class="foto-principal" 
          src="/static/imagens/social-media5.png">
      </div>

      <div class="w3-col l6">
        <div class="w3-col l6 w3-btn foto1">
          <div 
            id="texto-foto1"
            class="w3-left-align w3-col titulo-card-menor">
            {{titulo_card1}}
          </div>
          <div 
            id="sub-texto-foto1"
            class="w3-col w3-left-align titulo-card-menor">
           {{titulo_card2}}
          </div>
           <div 
            id="texto-foto1-inf"
            class="w3-col w3-left-align titulo-card-menor">
            <span class="w3-col">
              Lorem Ipsum available, <br/>
              but the <br/>
              suffered alterationsome <br/>
            </span>
            <div class='w3-col'>
              <i class="fa fa-linkedin w3-btn" aria-hidden="true"></i>
             
              <i class="fa fa-pinterest w3-btn" aria-hidden="true"></i>
             
              <i class="fa fa-twitter w3-btn" aria-hidden="true"></i>
            
              <i class="fa fa-facebook w3-btn" aria-hidden="true"></i>
            </div>
          </div>
          <img 
            class="foto1"
            src="/static/imagens/social-media1.png">

        </div>

        <div class="w3-col l6 w3-btn foto2">
          <div class="w3-col s6 m6 l6 w3-left-align">
             <div 
              id="texto-foto2"
              class=" w3-col titulo-card-menor">
              {{titulo_card1}}
            </div>

            <div 
              id="sub-texto-foto2"
              class="w3-col titulo-card-menor">
              {{titulo_card2}}
            </div>
          </div>

          <div class="w3-col s6 m6 l6 w3-left-align">
            <div 
              id="texto-foto2-inf"
              class="w3-col titulo-card-menor">
              <span class="w3-col">
                Lorem Ipsum available, <br/>
                but the <br/>
                suffered alterationsome <br/>
              </span>
              <div class='w3-col'>
                <i class="fa fa-linkedin w3-btn" aria-hidden="true"></i>
               
                <i class="fa fa-pinterest w3-btn" aria-hidden="true"></i>
               
                <i class="fa fa-twitter w3-btn" aria-hidden="true"></i>
               
                <i class="fa fa-facebook w3-btn" aria-hidden="true"></i>
              </div>
            </div>
          </div>
         
          <img 
            class="foto2 " 
            src="/static/imagens/social-media2.png">
        </div>

        <div class="w3-col l6 w3-btn foto3">
           <div class="w3-col s6 m6 l6 w3-left-align"
             style="margin-left:0px!important">
             <div 
              id="texto-foto3"
              class=" w3-col titulo-card-menor">
              {{titulo_card1}}
            </div>

            <div 
              id="sub-texto-foto3"
              class="w3-col titulo-card-menor">
              {{titulo_card2}}
            </div>

            <div class="w3-col s6 m6 l6 w3-left-align">
              <div 
                id="texto-foto3-inf"
                class="w3-col titulo-card-menor">
                <span class="w3-col">
                  Lorem Ipsum available, <br/>
                  but the <br/>
                  suffered alterationsome <br/>
                </span>
                <div class='w3-col'>
                  <i class="fa fa-linkedin w3-btn" aria-hidden="true"></i>
                 
                  <i class="fa fa-pinterest w3-btn" aria-hidden="true"></i>
                  
                  <i class="fa fa-twitter w3-btn" aria-hidden="true"></i>
                 
                  <i class="fa fa-facebook w3-btn" aria-hidden="true"></i>
                </div>
              </div>
            </div>
          </div>
          <img 
            class="foto3" 
            src="/static/imagens/social-media3.png">
        </div>

        <div class="w3-col l6 w3-btn foto4">
           <div class="w3-col s6 m6 l6 w3-left-align"
             style="margin-left:0px!important">
             <div 
              id="texto-foto4"
              class=" w3-col titulo-card-menor">
              BUSINESS
            </div>

            <div 
              id="sub-texto-foto4"
              class="w3-col titulo-card-menor">
              EVENTS
            </div>

            <div class="w3-col s6 m6 l6 w3-left-align">
              <div 
                id="texto-foto4-inf"
                class="w3-col titulo-card-menor">
                <span class="w3-col">
                  Lorem Ipsum available, <br/>
                  but the <br/>
                  suffered alterationsome <br/>
                </span>
                <div class='w3-col'>
                  <i class="fa fa-linkedin w3-btn" aria-hidden="true"></i>
                 
                  <i class="fa fa-pinterest w3-btn" aria-hidden="true"></i>
                
                  <i class="fa fa-twitter w3-btn" aria-hidden="true"></i>
               
                  <i class="fa fa-facebook w3-btn" aria-hidden="true"></i>
                </div>
              </div>
            </div>
          </div>
          <img 
            class="foto3"
            src="/static/imagens/social-media4.png">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
 
export default {
  name: 'Principal', 
  data () {
    return {
      titulo:'SOCIAL MEDIA POST',
      sub_titulo: 'Business Events',
      titulo_card1: 'BUSINESS',
      titulo_card2: 'EVENTS',
      ano: '2020',
      informacoes: 'Lorem Ipsum available,but the',
      cor: 'azul'
    }
  },
  methods:{
    mudandoCor(tipo){
      this.cor = tipo;
    },
    mudarCor(){
      return this.cor == 'verde'? 
        'background-image: linear-gradient(to bottom right, green 0, green 38%, #febe42 38%)!important':
        'background-image: linear-gradient(to bottom right, #004a89 0, #004a89 38%, #febe42 38%)!important';
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#ano{
  margin-top:30%;
  margin-left:50px!important;
}
#texto-principal{
 font-size:70px!important
}
#sub-texto-principal{
  color:#febe42!important;
  margin-top:10%;
}
#texto-principal-inf{
  margin-top:40%;          
  margin-left:50px!important; 
  font-size:30px!important;
  font-weight: normal;
}
#texto-foto1{
  font-size:30px!important
}
#sub-texto-foto1{
  color:#febe42!important; 
  margin-top:15%;
}
#texto-foto1-inf{
  color:white!important; 
  margin-top:70%; 
  margin-left:390px;
  font-weight: normal;
  font-size:20px!important;
}
#texto-foto2{
 font-size:30px!important;
 margin-top:72%;
 color:white!important;
}
#sub-texto-foto2{
  color:#febe42!important;
  margin-top:75%;
}
#texto-foto2-inf{
  color:white!important; 
  margin-top:72%;
  margin-left:400px;
  font-weight: normal;
  font-size:20px!important;
}

#texto-foto3{
  font-size:30px!important;
  margin-top:67%;
  color:#004a89!important;
}
#sub-texto-foto3{
  color:white!important;
  margin-top:70%;
}
#texto-foto3-inf{
  color:white!important; 
  margin-top:75%;
  margin-left:400px;
  font-weight: normal;
  font-size:20px!important;
}
#texto-foto4{
  font-size:30px!important;
  margin-top:67%;
  color:white!important;
}
#sub-texto-foto4{
  color:#febe42!important;
  margin-top:70%;
}
#texto-foto4-inf{
  color:white!important; 
  margin-top:75%;
  margin-left:400px;
  font-weight: normal;
  font-size:20px!important;
}
.titulo-card{
  color:white; 
  font-size:100px; 
  position:absolute; 
  margin-left:530px;
  font-weight: bold;
  margin-top: 5%;
}
.titulo-card-menor{
  color:#004a89; 
  font-size:50px; 
  position:absolute; 
  margin-left:85px;
  font-weight: bold;
  margin-top: 10%;
  z-index: 10;
}

.bloco-corpo{
  margin-top: 10%;
}
.principal{
  position: relative;
  z-index: 2 !important;
  width: 100rem;
  height: 100rem;
  margin-left:5%;
  box-shadow: rgb(95, 95, 95) 3px 0px 50px 3px;
  background-image: linear-gradient(to bottom , #004a89 0, #004a89 70%, #febe42 30%);
  
}
.titulo{
  font-size: 100px;
  color:white;
}
.sub-titulo{
  font-size: 50px;
  color:white;
}
.cabecalho{
  position: fixed;
  z-index: 0;
  width: 100%;
  height: 100%;
  background-image: linear-gradient(to bottom right, #004a89 0, #004a89 38%, #febe42 38%);
}
.foto-principal{
  position: relative;
  z-index: 2 !important;
  background-size: 100%;
  width: 100%;
  height: 100%;
 
}
.foto1{
 position: relative;
  z-index: 2 !important;
  background-size: 100%;
  width: 50rem;
  height: 50rem;
  padding: 30px;
}
.foto2{
  position: relative;
  background-size: 100%;
  width: 50rem;
  height: 50rem;
  z-index: 2 !important;
  padding: 30px;
}
.foto3{
  position: relative;
  background-size: 100%;
  width: 50rem;
  height: 50rem;
  z-index: 2 !important;
  padding: 30px;
}
.foto4{
  position: relative;
  background-size: 30px;
  width: 50rem;
  height: 50rem;
  z-index: 2 !important;
  padding: 30px;
}
@media only screen and (max-width: 600px) {
  .bloco-corpo{
    margin-top: 15%;
  }
  #ano{
    margin-top:30%;
    margin-left:0px!important;
    font-size: 25px;
  }
  .cabecalho{
    position:fixed;
  }
  .titulo{
    font-size: 20px;
    color:white;
  }
  .sub-titulo{
    font-size: 15px;
    color:white;
  }
  .foto4{
    position: relative;
    background-size: 15px;
    width: 15rem;
    height: 15rem;
    z-index: 2 !important;
    padding: 15px;
  }
  .foto3{
    position: relative;
    background-size: 100%;
    width: 15rem;
    height: 15rem;
    z-index: 2 !important;
    padding: 15px;
  }
  .foto1{
  position: relative;
    z-index: 2 !important;
    background-size: 100%;
    width: 15rem;
    height: 15rem;
    padding: 15px;
  }
  .foto2{
    position: relative;
    background-size: 100%;
    width: 15rem;
    height: 15rem;
    z-index: 2 !important;
    padding: 15px;
  }
  .foto-principal{
    position: relative;
    z-index: 2 !important;
    background-size: 100%;
    width: 15rem;
    height: 15rem;

  
  }
  .principal{
    position: relative;
    z-index: 2 !important;
    width: 15rem;
    height: 15rem;
    margin-left:5%;
    box-shadow: rgb(95, 95, 95) 3px 0px 50px 3px;
    background-image: linear-gradient(to bottom , #004a89 0, #004a89 70%, #febe42 30%);
    
  }
  .titulo-card{
    color:white; 
    font-size:50px; 
    position:absolute; 
    margin-left:300px;
    font-weight: bold;
    margin-top: 5%;
  }

  .titulo-card-menor{
    color:#004a89; 
    font-size:25px; 
    position:absolute; 
    margin-left:50px;
    font-weight: bold;
    margin-top: 10%;
    z-index: 10;
  }
  #texto-principal{
   font-size:20px!important;
   margin-left: 78px!important;
  }
  #sub-texto-principal{
    color:#febe42!important;
    margin-top:13%;
    margin-left: 78px!important;
    font-size: 20px!important;
  }
  i{
    padding: 0px;
  }
  #texto-principal-inf{
    margin-top:45%;          
    margin-left:0px!important; 
    font-size:5px!important;
    font-weight: normal;
  }
  #texto-foto1{
    font-size:10px!important;
    margin-left:30px!important; 
  }
  #sub-texto-foto1{
    color:#febe42!important; 
    margin-top:15%;
    font-size: 10px!important;
    margin-left:30px!important; 
  }
  #texto-foto1-inf{
    color:white!important; 
    margin-top:70%; 
    margin-left:120px;
    font-size: 5px!important;
    font-weight: normal;
  }
  #texto-foto2{
    font-size:10px!important;
    margin-top:70%;
    margin-left:25px;
    color:white!important;
  }
  #sub-texto-foto2{
    color:#febe42!important;
    margin-top:75%;
    margin-left:25px;
    font-size:10px!important;
  }
  #texto-foto2-inf{
    color:white!important; 
    margin-top:72%;
    margin-left:110px;
    font-weight: normal;
    font-size:5px!important;
  }

  #texto-foto3{
    font-size:10px!important;
    margin-top:66%;
    margin-left:20px!important;
    color:#004a89!important;
  }
  #sub-texto-foto3{
    font-size:10px!important;
    color:white!important;
    margin-top:70%;
    margin-left:20px!important;
  }
  #texto-foto3-inf{
    color:white!important; 
    margin-top:75%;
    margin-left:110px;
    font-weight: normal;
    font-size:5px!important;
  }
  #texto-foto4{
    font-size:10px!important;
    margin-top:70%;
    margin-left:25px;
    color:white!important;
  }
  #sub-texto-foto4{
    color:#febe42!important;
    margin-top:75%;
    margin-left:25px;
    font-size:10px!important;
  }
  #texto-foto4-inf{
    color:white!important; 
    margin-top:72%;
    margin-left:110px;
    font-weight: normal;
    font-size:5px!important;
  }
}
</style>
