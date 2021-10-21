My personal repository
<div>
<h3>
I am an energetic, tenacious person in all the projects I propose. Working with professionalism and responsibility together with other people or independently. Working now, as a FullStack Web developer.I always mention that the best way to ensure that your goals are realized is to work with integrity and conviction.:blue_heart:</h3></div>



<div>
  <svg class="aksr" version="1.1"  x="0px" y="0px"
 xml:space="preserve">
    <defs>
      <pattern id="water" width=".25" height="1.1" patternContentUnits="objectBoundingBox">
        <path class="littlePath"
          d="M0.25,1H0c0,0,0-0.659,0-0.916c0.083-0.303,0.158,0.334,0.25,0C0.25,0.327,0.25,1,0.25,1z" />
      </pattern>
      <text class="container" id="text">•A •K •S •R</text>
      <mask id="text-mask">
        <use x="0" y="0" href="#text" />
      </mask>
      <g id="eff">
        <use x="0" y="0" href="#text" />
        <rect class="water-fill" mask="url(#text-mask)" fill="url(#water)" x="-300" y="50" width="1200" height="120"
          opacity="0.3">
          <animate attributeType="xml" attributeName="x" from="-300" to="0" repeatCount="indefinite" dur="2s" />
        </rect>
        <rect class="water-fill" mask="url(#text-mask)" fill="url(#water)" y="45" width="1600" height="120"
          opacity="0.3">
          <animate attributeType="xml" attributeName="x" from="-400" to="0" repeatCount="indefinite" dur="3s" />
        </rect>

        <rect class="water-fill" mask="url(#text-mask)" fill="url(#water)" y="55" width="900" height="120"
          opacity="0.3">
          <animate attributeType="xml" attributeName="x" from="-200" to="0" repeatCount="indefinite" dur="1.4s" />
        </rect>
        <rect class="water-fill" mask="url(#text-mask)" fill="url(#water)" y="55" width="2000" height="120"
          opacity="0.3">
          <animate attributeType="xml" attributeName="x" from="-500" to="0" repeatCount="indefinite" dur="2.8s" />
        </rect>
      </g>
    </defs>
    <use href="#eff" class="use" />
  </svg>
  
</div>

<div class="header">
  <!--Content before waves-->
  <div class="inner-header flex">
    <!--Just the logo.. Don't mind this-->
    <svg version="1.1" class="logo" baseProfile="tiny" id="Layer_1" xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" viewBox="0 0 500 500" xml:space="preserve">
      <path fill="#FFFFFF" stroke="#000000" stroke-width="10" stroke-miterlimit="10" d="M57,283" />
    </svg>
  </div>
  <div class="container">
    <h3>
      Soy una persona enérgica, tenaz en todos los proyectos que me propongo.
      Trabajando con profesionalidad y responsabilidad junto a otras personas o de
      manera independiente. Desempeñándome ahora, como desarrolladora Web FullStack.
      Siempre mencionó, que la mejor forma de garantizar que tus metas estén
      realizadas. Es trabajar con entereza y convicción.
    </h3>
    </div>
  <div>
    <svg class="waves" 
      viewBox="0 24 150 28" preserveAspectRatio="none" shape-rendering="auto">
      <defs>
        <path id="gentle-wave" d="M-160 44c30 0 58-18 88-18s 58 18 88 18 58-18 88-18 58 18 88 18 v44h-352z" />
      </defs>
      <g class="parallax">
        <use class="ola" xlink:href="#gentle-wave" x="48" y="0" fill="rgba(255,255,255,0.7" />
        <use class="ola" xlink:href="#gentle-wave" x="48" y="3" fill="rgba(255,255,255,0.5)" />
        <use class="ola" xlink:href="#gentle-wave" x="48" y="5" fill="rgba(255,255,255,0.3)" />
        <use class="ola" xlink:href="#gentle-wave" x="48" y="7" />
      </g>
    </svg>
  </div>
  <!--Waves end-->
</div>

<!-- Content starts
<div class="content flex">
  <p>Anny Karolina Sánchez Rodríguez | 2021 | </p>
</div> -->

<style>
  body {
  text-align: center;
  background-size: cover;
  background-position: 100%;
  height: 100px;
  margin:0;
}
.aksr {
  z-index: 99;
  position: absolute;
  top: 25%;
  margin-top: -60px;
  margin-left: 150px;
  font-family: 'Do Hyeon', sans-serif;
  width: 990px;
  height: 240px ;
}
use {
  opacity: .9;
  mix-blend-mode: color-burn;
  fill: #ec07a8 ;
}
text {
transform: translate(1%, 48%);
font-size: 9rem;
font-weight: 900;
}
#littlePath{
  fill: rgb(156, 165, 247);
}
.container {
  width: 100%;
  padding-right: 15px;
  padding-left: 15px;
  margin-right: auto;
  margin-left: auto;
  max-width: 960px;
}
.row {
  display: flex;
  flex-wrap: wrap;
  margin-right: -15px;
  margin-left: -15px;
}
#content {
  width: 100%;
  margin-left: 10rem;
  transition: all 0.4s;
}
.header {
  width: 100%;
  position: relative;
  text-align:center;
  background: linear-gradient(60deg, rgb(21, 121, 253) 0%, rgb(132, 188, 253) 100%);
  color:rgb(255, 255, 255);
}
.inner-header {
  height: 65vh;
  width: 100%;
  margin: 0;
  padding: 0;
}
.flex { 
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.waves {
  position:relative;
  width: 100%;
  height: 20vh;
  margin-top: 20%;
  margin-bottom: -7px; /*Fix for safari gap*/
  min-height: 100px;
  max-height: 150px;
}
.logo {
  width:50px;
  fill:rgb(255, 255, 255);
  padding-right:15px;
  display:inline-block;
  vertical-align: middle;
}
.ola{
  fill: #2537df;
}
.parallax > use {
  animation: move-forever 25s cubic-bezier(.55,.5,.45,.5)     infinite;
}
.parallax > use:nth-child(1) {
  animation-delay: -2s;
  animation-duration: 7s;
}
.parallax > use:nth-child(2) {
  animation-delay: -3s;
  animation-duration: 10s;
}
.parallax > use:nth-child(3) {
  animation-delay: -4s;
  animation-duration: 13s;
}
.parallax > use:nth-child(4) {
  animation-delay: -5s;
  animation-duration: 20s;
}
@keyframes move-forever {
  0% {
   transform: translate3d(-90px,0,0);
  }
  100% { 
    transform: translate3d(85px,0,0);
  }
}
/*Shrinking for mobile*/
@media (max-width: 768px) {
  .waves {
    height:50px;
    min-height:50px;
  }
  h3{
    font-size: 18px;
  }
  .aksr{
    z-index: 99;
    
    font-family: 'Do Hyeon', sans-serif;
    margin: 0;  
  }
}
h3 {
  font-family: 'Do Hyeon', sans-serif;
  font-size: 22px;
  font-weight:300;
  letter-spacing: 2px;
  margin: -50px;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fafafa;
  width: 100%;
  margin-left: -15px;
  right: 530px;
}
</style>


