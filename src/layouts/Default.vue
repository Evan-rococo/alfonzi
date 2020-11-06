<template>

  <div class="layout">
    <div class="header">
      <a href="#default" class="logo"><g-link to="/">HOT REQUEST</g-link></a>
    </div>

    <div class="sidebar">
      <div class="Sidebar" v-bind:class="{ open: isActive}" style="opacity:100%;">
        <g-link to="/newstuff/">NEW STUFF</g-link><br>
            <g-link to="/boogie/">BOOGIE</g-link><br>
            <g-link to="/esoteric/">ESOTERIC</g-link><br>
            <g-link to="/pop/">POP MUSIC</g-link><br>
            <g-link to="/reggae/">REGGAE</g-link><br>
            <g-link to="/tropical/">TROPICAL</g-link><br>
             <br>
            <g-link to="/faq/">FAQ</g-link><br>
            <g-link to="/contact/">CONTACT</g-link><br>
            <br>
            <g-link to="/cart/">CART (0)</g-link><br>
            <g-link>SEARCH</g-link><br>
            <!-- <form class="example" action="/action_page.php" autocomplete="off">
  <input type="search" placeholder="search" name="search" >
  <button type="submit"><i class="fa fa-search"></i></button>
</form> -->


</div>
<div class="Hamburger"  @click.prevent="toggleClass">
    <h6>MENU</h6>
        
    
 
</div>
    </div>
    <slot/>
    <div class="footer">
      <footer>
       <div class="flex-container">
  <div class="flex-container1">
  <div class="flex-item-left1"><g-link to="/">INSTAGRAM</g-link></div>
  <div class="flex-item-left2"><g-link to="/">BLOG</g-link></div></div>
  <div class="flex-container2">
  <div class="flex-item-right1"><g-link to="/">NEWSLETTER</g-link></div>
  <div class="flex-item-right2">COPYRIGHT 2020</div></div>
</div>
      </footer>
    </div>
  </div>
</template>

<script>
 export default {
        data: () => ({
            isActive: false
        }),
        methods: {
           toggleClass: function(event){
       this.isActive = !this.isActive;
    }
        }
    }
</script>

<style>
/* unvisited link */
a:link {
  color: black;
  text-decoration: none;
  text-emphasis: none;
  font-size:1em;
  line-height: 1em;
}

ul{
  display: flex;
  list-style: none;
  font-size:  1.67em;
  text-align: right;
  margin-left: 2vw;
}

li:nth-child(2n){
  margin-left: .5rem;
  margin-right: .5rem;
}

/* visited link */
a:visited {
  color: black;
}

/* mouse over link */
a:hover {
  color: red;
}

body {
  font-family: "Arial Rounded MT Bold";
  margin:0;
  line-height: 1;
  width: 100%;
  overflow-x: hidden;
  }

.h1 {
  font-family: "Arial Rounded MT Bold";
  font-size:  2em;
  }

.h12 {
  font-family: "Arial Rounded MT Bold";
  font-size:  1em;
  }

.p {
  font-family: "Helveesti";
  font-size: calc(16px + 1vw);
  line-height: calc(1.1em + 0.5vw);
  font-weight: normal;
  
  }
  
h2 {
  font-family: "Arial Rounded MT Bold";
  font-size: 1.5em;
  font-style: normal;
  font-weight: normal;

  }

h3 {
  font-family: "Arial Rounded MT Bold";
  text-align: right;
  font-size: 1.5em;
  font-weight: normal;

  }

h4 {
  text-align: right;
  font-family: "Arial Rounded MT Bold";
  font-size: 1.25em;
  font-weight: normal;
 
  }

h5 {
  font-family: "Arial Rounded MT Bold";
  font-size: 1.25em;
  font-weight: normal;
  }

h6 {
  font-style: normal;
  font-family: "Arial Rounded MT Bold";
  font-size: 2em;
  font-weight: normal;
}

.logo {
  font-family: "Arial Rounded MT Bold";
  text-align: center;
  text-shadow: 3px 5px 3px none;
  z-index: 4;
  font-weight: normal;
  }
.layout {
  width: 100%;
  margin-right: 0em;
  padding-left: 0px;
  padding-right: 0vw;
  }
.nav__link {
  margin-left: 0px;
  text-decoration: none;
  color: black;
  }

.header {
  overflow: hidden;
  margin-top: 3.67em;
  position: relative;
   text-align: center;
  }

.header a {
  color: none;
  text-align: center;
  }

.sticky {
  position: fixed;
  top: 0;
  width: 100%;
  }

.header a.logo {
  font-size: 4em;
  }

.header a:hover {
  background-color:none;
  color: red;
  }

.header a.active {
  background-color:none;
  color: black;
  }

.header-right {
  float: right;
  font-size: 2em;
  margin-right: 9vw;
  background-color: none;
  }

@media screen and (max-width: 70em) {
   .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
  .container{
    display: block;
    margin-left: 27vw;
    }
    
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 450px;
    }

  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;
    }
  
  .right{
    width: 33%;
    background-color: none;
    }

  .header a {
    background-color: none;
    }
    
  .header-right {
    float: fixed;
    background-color: none;
  }
}

@media (max-width: 48em) {
  .header a {
    float: right;
    display: block;
    background-color:none;
    width:100%;
    }

  .header a.logo {
  font-size: 3em;
  margin-left: 8em;
  }

  .header {
    float: right;
    display: block;
    position: fixed;
    margin-top: -5.34em;
    background-color: none;
    }
    
  .header-right {
    font-size: 1.5em;
    position: relative;
    left: 0;
    top: 0;
  }

  ul{
  display: flex;
  list-style: none;
  font-size:  1.34em;
  text-align: center;}
}

@media screen and (max-width: 33em) {
  .container {
    background: none;
    display: flex;
    flex-flow: wrap;
    }
.item {
  text-align: left;
  }

.left, .right{
  display: contents;
}
.item1, .item2{
  order: 1;
}
.item4, .item6{
  order: 2;
}
.item5, .item3{
  order: 3;
}
.header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  background-color:none;
}

.header {
  position: fixed;
  left: 0;
  top: 0;
  margin-top:.67em;
  background-color: none;
} 
    
.header-right {
  float: left;
  margin-left:3em;
  position: fixed;
  left: 0;
  top: 0;
  }
}

form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1.67em;
  float: left;
  width: 100%;
  padding-left:0em;
  background: none;
  text-decoration: black;
}

form.example button {
  float: left;
  width: 10%;
  padding: 0px;
  color: none;
  border: none;
  cursor: pointer;
  margin-left:0em;
  outline: 0px solid transparent;
}

form.example button:hover {
  background: red;
  border: none;
}

form.example::after {
  content: "";
  clear: both;
  display: table;
  font-family: 'elmo';
  text-decoration: black;
  
}


.navbar a:hover {
  color: red;
}
/* Main content */
.main {
  margin-top: 0px;}
.Sidebar {
  background:none; opacity: 100%;
  position: fixed;
  top: 5.78em;
  bottom: 0;
  left: 0;
  z-index: 6;
  margin-left: 8vw;
  font-size: 1.67em;
  width: 7em;
}
.Hamburger {
  position: fixed;
  margin-top: 0em;
  opacity: 100;
  z-index: 6;
  margin-left:3vw;
  background-color: none;
  height: 45em;
}
@media (max-width: 48em) {

  .header a {
  float: right;
  display: block;
  position: relative;
  text-align: center;
  }
  .Sidebar {
    transform: translate3d(-300%, 0, 0);
  }
  .Hamburger {
    opacity: 100%;
    margin-left:2.5vw;
     z-index: 6;
  }
 
  .Sidebar.open {
    transform: translate3d(0, 0, 0);
     z-index: 6;
     margin-top:-3em;
  }

     .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 23vw;
  }
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 42vw;}
  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;
    }
  
  .right{
    width: 36%;
    background-color: none;
  } 
  
  .topnav a, .topnav input[type=text] {
    float: none;
    display: block;
    text-align: left;
    width: 100%;
    margin: 0;
    padding: 1.2em;
        }
  }
  

    form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 100%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background:none;
  text-decoration: black;
}


@media (min-width: 48em){
  
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 23vw;
  }
  .left{
    width: 63%;
    margin-right: 2em;
    max-width: 42vw;
    }

  .item1 {
    opacity: 100%;
    }

  .item3 {
    background-color: none;
    text-decoration: none;}
  
  .right{
    width: 36%;
    background-color: none;
    } 

  

    form.example input[type=text] {
  font-family: 'elmo';
  font-size: 1em;
  float: left;
  width: 90%;
  border: none;
  outline: 0px solid transparent;
  padding-left:0em;
  background: none;
  text-decoration: black;
}
  }

@media (max-width: 70em) {
  .Hamburger {
  position: fixed;
  margin-top: -9em;
  opacity: 0%;
  z-index: 6;
  height: 1em;

  margin-left:2.5vw;}

  .Sidebar {
  position: fixed;
  top: 5.85em;
  opacity: 100%;
  z-index: 0;
  margin-left: 2.34vw;
  width: 6em;
  line-height:1.125em;
  background-color:none;
  }
  }

.Button {
  position: absolute;
  top: 0.5em;
  right: 0.5em;
  width: 4em;
}

.main {
  font-size: 2em;
}

ul{
  display: flex;
  list-style: none;
  font-size:  1.34em;
  text-align: right;
  padding-top:.7em;
}

.topnav input[type=text] {
  float: right;
  border: none;
  margin-top: 1em;
  margin-right: 1.8em;
  margin-left: 3vw;
  position: relative;
}

.sticky {
  position: relative;
  top: 0;
  width: 100%;}

.marquee {
            height: 1.67em;
            overflow: hidden;
            position: relative;
            background:none;
            color: black;
            align-items:baseline;
        }
        
        .marquee p {
            position: fixed;
            width: 400%;
            height: 100%;
            margin: 0;
            line-height: 2em;
            text-align: center;
            -moz-transform: translateX(100%);
            -webkit-transform: translateX(100%);
            transform: translateX(200%);
            -moz-animation: scroll-left 1s linear infinite;
            -webkit-animation: scroll-left 1s linear infinite;
            animation: scroll-left 15s linear infinite;
        }
        
        @-moz-keyframes scroll-left {
            0% {
                -moz-transform: translateX(100%);
            }
            100% {
                -moz-transform: translateX(-100%);
            }
        }
        
        @-webkit-keyframes scroll-left {
            0% {
                -webkit-transform: translateX(100%);
            }
            100% {
                -webkit-transform: translateX(-100%);
            }
        }
        
        @keyframes scroll-left {
            0% {
                -moz-transform: translateX(100%);
                -webkit-transform: translateX(100%);
                transform: translateX(100%);
            }
            100% {
                -moz-transform: translateX(-100%);
                -webkit-transform: translateX(-100%);
                transform: translateX(-100%);
            }
        }
        
  .footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
}
table, td, th {
  border: 0px solid black;
}
table {
  border-collapse: collapse;
  width: 100%;
}
td {
  width: 50%;
  vertical-align: top;
  background-color:none;
}
img {
  max-width: 100%;
  display: block;
}
p {
  margin: 0 0 0 0;
}
.container {
  display: flex;
  flex-direction: column;
  margin-left: 26vw;
  margin-bottom: 8em;
  background-color:none;}
.left {
  width: 100%;
}
.right{
  width: 37%;}
  
   @media (max-width: 48em) {
     .Hamburger {
  margin-left: 5vw;
   z-index: 6;
}
      .footer {
  position: fixed;
  left: 0;
  bottom: 0;
  width: 100%;
}
     .Sidebar {
      border-radius: 25px;
      background:white;
      margin-left:.25em;
      margin-top: -3em;
      padding-left:.34em;
      padding-top: .67em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 15em;
      width: 7em;
      box-shadow: 2px 6px 6px 0px black;
        }

        
      }
@media (min-width: 70em) {
       * {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1.67em;
  text-align: center;
  background-color: yellow;
  border-radius: 25px;
}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
  background-color: orangered;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
  background-color: purple;
}

.flex-item-left1 {
  background-color: green;
  padding-top: .67em;
  padding-bottom:.125em;
  padding-left: 1vw;
  padding-right: 1vw;
  margin-right: 1vw;
  flex: 10%;
}

.flex-item-left2 {
  background-color: whitesmoke;
  padding: .67em;
  margin-left: 1vw;
  flex: 10%;
}

.flex-item-right1 {
  background-color: chartreuse;
  margin-right: 1vw;
  padding:.67em;
  flex: 10%;
}

.flex-item-right2 {
  background-color:cyan;
  margin-left: 1vw;
  padding:.67em;
  flex: 10%;
}

      .Hamburger {
      margin-top: -8vw;
      z-index: 6;
      opacity: 0;}

  .Sidebar {
   position: fixed;
   background:none;
   top: 5.85em;
   bottom: 0;
   left: 0;
   background:none;
   opacity: 100%;
   z-index: 0;
   margin-left: 8.34vw;
   width: 6em;
   line-height:1.125em;
  }

      }
    
  @media (min-width: 48em) {
       * {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1.34em;
  text-align: center;
  margin-bottom:.67em;
  margin-left:23vw;
  margin-right: 1.67vw;
  background-color: yellow;
  border-radius: 25px;
}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
  margin-left: 4vw;
  margin-right: 2vw;
  background-color: orangered;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
  margin-right: 1vw;
  margin-left: 1vw;
  background-color: aqua;

}

.flex-item-left1 {
  background-color: none;
  padding-top: .5em;
  padding-bottom:.5em;
  flex: 10%;
}

.flex-item-left2 {
  background-color: none;
  padding-top: .5em;
  padding-bottom:.5em;
  flex: 10%;
}

.flex-item-right1 {
  background-color: none;
  padding-top:.5em;
  padding-bottom:.5em;
  flex: 10%;
}

.flex-item-right2 {
  background-color:none;
  padding-top:.5em;
  padding-bottom:.5em;
  flex: 20%;
}
  }
    
    @media (max-width: 48em) {
     * {
  box-sizing: border-box;
}

.flex-container {
  display: flex;
  flex-direction: row;
  font-size: 1.34em;
  text-align: center;
  margin-bottom:.67em;
  margin-left:3vw;
  margin-right: 3vw;
  background-color: yellow;
  border-radius: 25px;
}

.flex-container1 {
  display: flex;
  flex-direction: row;
  text-align: center;
}

.flex-container2 {
  display: flex;
  flex-direction: row;
  text-align: center;
}

.flex-item-left1 {
  background-color: none;
  padding-top: .34em;
  padding-bottom:.125em;
  flex: 10%;
}

.flex-item-left2 {
  background-color: none;
  padding-top: .34em;
  padding-bottom:.125em;
  flex: 10%;
}

.flex-item-right1 {
  background-color: none;
  padding-top: .125em;
  padding-bottom:.34em;
  flex: 10%;
}

.flex-item-right2 {
  background-color: none;
  padding-top: .125em;
  padding-bottom:.34em;
  flex: 10%;
}

.Hamburger {
  position: fixed;
  margin-top: -9.67em;
  opacity: 100;
  z-index: 6;
  margin-left:5vw;
  font-size: .8em;
  background-color: none;
  height: 4em;}
  }

  @media (max-width: 48em) {
  .flex-container {
    flex-direction: column;
  }
}
</style>
