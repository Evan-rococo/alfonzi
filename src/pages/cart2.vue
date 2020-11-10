<template>
  <Layout>
   
    <nav  style="margin-bottom:1.34em; margin-top:4em;">
       <ol>MORE GOOD RECORDS..</ol>

<div class="flex-container" style="padding:1.67vw;">
  <div class="flex-item-left">


       <div class="flex-container3">
  <div class="flex-item-left3"><g-link to="/product/">
    <g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
    </g-link></div>
  <div class="flex-item-right3">
    <p style="margin-bottom:.34em">"YOU KNOW YOU FEEL IT" LP</p>
     <p>KUMASI</p>
  </div>
</div>

</div>
  <div class="flex-item-right">
    
    
    <div class="flex-container3">
  <div class="flex-item-left3"><g-link to="/product/">
    <g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897448/p1_jy7ug9.png"/>
    </g-link></div>
  <div class="flex-item-right3">
     <p style="margin-bottom:.34em">TENDER LOVER 7"</p>
     <p>EDDY ALIMANTE</p>

  </div>
</div>

</div></div>
</div></nav>

  </Layout>
</template>

<style>
* {
  box-sizing: border-box;
}

.flex-container3 {
  
  display: flex;
  flex-direction: column;
  text-align: left;
}

.flex-item-left3 {
  background-color: #f1f1f1;
  flex: 50%;
  margin-bottom: .67em;
}

.flex-item-right3 {
  background-color: none;
  padding-left:.67em;
  font-size: calc(.34em + 2vw);
  text-align: left;
  flex: 50%;
}

/* Responsive layout - makes a one column-layout instead of two-column layout */
@media (max-width: 48em) {
  .flex-container3 {
    flex-direction: row;
  }
}


@media (max-width: 33em) {
  .flex-container3 {
  display: flex;
  text-align: left;
}

.flex-item-left3 {
  background-color: #f1f1f1;
  flex: 50%;
  box-shadow: 0px 6px 6vw 1vw black;
}

.flex-item-right3 {
  background-color: none;
  font-size: calc(.34em + 2vw);
  text-align: left;
  flex: 50%;}

  .ol{ 
  font-size: 3em;
  margin-left: 66vw;}

  
 
 }

@media (max-width: 48em) {
  nav {
    border-radius: 25px;
    margin-left:3vw;
    margin-right:3vw;
    background-color:red;}

  .flex-item-left3 {
  background-color: #f1f1f1;
  flex: 50%;
  max-width: 36vw;
  margin-bottom: .34em;
  box-shadow: 0px 6px 6vw 1vw black; }
   
}

@media (min-width: 48em){
  nav {
    margin-left: 25vw;
    margin-right: 3vw;
    border-radius: 25px;}

  .flex-container {
    background-color: none;
    margin-bottom: 6em;
  }
  .flex-container3 {
  display: flex;
  flex-direction: column;
  text-align: left;
  margin-left: .34vw;
  margin-right: .34vw;}


  .flex-item-left3 {
  background-color: #f1f1f1;
  flex: 50%;
  max-width: 36vw;
  margin-bottom: .34em;
  box-shadow: 0px 6px 6vw 1vw black;

}

  .flex-item-right3 {
  background-color: none;
  max-width: 36vw;
  font-size: calc(.67em + .34vw);
  text-align: left;
  flex: 50%;
}

}

@media (min-width: 70em){

  }
  

 
</style>