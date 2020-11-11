<template>
  <Layout>
   
    <div class="row">
  <div class="column">
    <div class="app">

      <g-image src="https://res.cloudinary.com/winenot/image/upload/v1604715482/IMG_1332_povddi.jpg"/>
      <h3>PATIENCE IS BITTER, BUT IT'S FRUIT IS REAL SWEET.</h3>

     </div>
  </div>
  <div class="column">
    <p>A frattura del pene o peniena, anche denominata sindrome del chiodo rotto, è un raro trauma del pene che consiste nell'improvvisa e dolorosa <br>rottura della tonaca albuginea dei corpi cavernosi, dovuta a un colpo violento verificatosi durante l'erezione. Traumi simili, se avvenuti a pene flaccido ad esempio durante l'attività sportiva o per l'utilizzo di armi da fuoco, non vengono invece definiti fratture, ma semplici traumi penieni.</p>
  </div>
</div>
 <iframe src="https://open.spotify.com/embed/playlist/7hh5ZtxuXTt1ar4XoFDLCN" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'ALFON'
  }
}
</script>

<style>
* {
  box-sizing: border-box;
}

/* Create two equal columns that floats next to each other */
.column {
  float: left;
  width: 50%;
  
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 56em) {
  .column {
    width: 100%;
    margin-bottom: 1.34em;}
    }

.home-links a {
  margin-right: 1em;}


@media (min-width: 48em){

  .column {
    margin-bottom: 1.67em;
  }
   iframe {
    width: 70vw;
    height: 50vw;
    border-radius: 25px;
    margin-left:25.8vw;
    margin-bottom: 9em;
    box-shadow: 0px 0px 6vw 7px green;
  }

 p {
   font-family:ABC Helveesti Trial;
   margin-right:4vw;
   font-size: 1.25em;
   line-height: 1.125;
   margin-bottom: 5vw;
 }

.app{
  margin-right:1.5em;
  text-align: center;
}

.row {
  margin-top:2em;
  margin-left: 13em;
}

h3{
  margin-top: .34em;
  font-size: 2.67vw;
  line-height: 1.125;
  font-style: normal;
  text-align: center;
}


#img{
  height: 135px;
  width: 135px;}

}

@media (max-width: 48em){
  iframe {
    width: 90vw;
    height: 66vw;
    border-radius: 25px;
    margin-left:5vw;
    margin-bottom: 9em;
    box-shadow: 0px 0px 6vw 7px green;
  }
 p {
   font-family:ABC Helveesti Trial;
   margin-right:3vw;
   margin-left:3vw;
   font-size: 1.34em;
   line-height: 1.125;
   margin-bottom:5vw;
 }

.app{
  display: grid;
   margin-right:3vw;
   margin-left:3vw;
   text-align: center;}

  .row {
    background-color: none;
    margin-top:6em;
  }

h3{
  font-size: 3.34vw;
  margin-top: .34em;
  font-style: normal;
  text-align: center;
}

#img{
  height: 35px;
  width: 35px;}

.left, .right{
  display: contents;}

}

@media (max-width: 33em){
  .row {
    background-color: none;
    margin-top:6em;}

   p {
   font-family:ABC Helveesti Trial;
   margin-right:3vw;
   margin-left:3vw;
   margin-bottom:5vw;
   line-height: 1.125;
 }

.app{
  display: grid;
   margin-left:5vw;
   margin-right:5vw;
   text-align: center;
}

h3{
  font-size: 3.34vw;
  margin-top: .34em;
  font-style: normal;
  text-align: center;
}

#img{
  height: 35px;
  width: 35px;}

.left, .right{
  display: contents;}


.item1{
  order: 1;}

.item2{
  order: 2;
  margin-left:2vw;
  margin-right:2vw;
  margin-bottom:6em;}
}

@media (min-width: 70em){
   iframe {
    width: 70vw;
    height: 35vw;
    border-radius: 25px;
    box-shadow: 0px 0px 6vw 7px green;
    margin-left:25.67vw;
    margin-bottom: 9em;
  }
  .row {
  margin-top:2em;
  margin-left: 24vw;
  margin-bottom: 2.5vw;
  background-color: none;}
  .app {
    line-height: 1.25;
    background-color: none;
  }
  p{
    font-size:1.34em;
    background-color: none;
  }

  h3 {
    margin-top: .34em;
    font-size: 1.34vw;}
  }

@media screen and (min-width: 56em) {
  h3 {
    margin-top: .34em;
    font-size: 1.34vw;}
    }


</style>
