<template> 
    <div> 
        <form action="/action_page.php">
  <div class="row2">
    <div class="col-25" style="margin-right:1em;margin-bottom:.34em;">
      <label for="name">NAME</label>
    </div>
    <div class="col-75" style="text-align:right;">
      <input type="text" id="name" name="name" style="text-align:right; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;" placeholder="">
    </div>
  </div>
  <div class="row2">
    <div class="col-25" style="margin-right:1em;margin-bottom:.34em;">
      <label for="lname">EMAIL ADDRESS</label>
    </div>
    <div class="col-75" style="text-align:right;">
      <input type="text" id="email" name="email" style="text-align:right; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;" placeholder="">
    </div>
  </div>
  <div class="row2">
    <div class="col-25" style="text-align:right; margin-right:1em; margin-bottom:.34em;">
      <label for="topic">TOPIC</label>
    </div>
    <div class="col-75">
      <select id="topic" name="topic" style="color:black; background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;">
        <option value="request"></option>
        <option value="request">Make a request</option>
        <option value="before">Before order</option>
        <option value="after">After order</option>
      </select>
    </div>
  </div>
  <div class="row2">
    <div class="col-25" style="margin-right:1em;margin-bottom:.34em;">
      <label for="subject">ADDITIONAL INFO</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="" style="text-align:right; background-color:whitesmoke; height:3em;border-radius: 25px; padding:.34em; padding-right:1em;margin-bottom:.67em;" ></textarea>
    </div>
  </div>
   <div class="row2">

    <div class="col-26" style="text-align:center; font-size:1.5em; margin-right:0em;" >
      <input type="submit" style="background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-right:.8em; padding-left:.8em;" value="SUBMIT">
    </div></div>
  
  </form>
    </div>
</template>

<script>
export default {
    components: {
        name: 'Form'
    }
}
</script>
<style scoped>

@media (max-width: 33em) {
 }

@media (max-width: 48em) {
 .col-25 {
  text-align: right;
  margin: 0em;
  padding:0em;
  }

.col-26 {
  margin-bottom:9em;
  }

.col-75 {
  text-align: right;
  margin: 0em;
  padding:0em;
  background-color:none;
  }
}

@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
     }
     
  .col-25 {
  text-align: right;
  color: black;
  font-size: 1.125em;
  border-radius: 25px;
  margin-right:1em;
  margin-bottom: .34em;
  }

  .col-26 {
  margin-bottom:6em;
  }

  .col-75 {
  text-align: right;
  color: black;
  font-size: 1.125em;
  border-radius: 25px;
  margin-bottom:.34em;
  }

  .col-25 {
  text-align: right;
  color: black;
  font-size: 1.67em;
  }

  .col-75 {
  text-align: right;
  color: black;
  font-size: 1.34em;
  }
}

@media (min-width: 70em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
    }
  
    .row {
margin-right:7.34vw;
    }

  .col-25 {
  text-align: right;
  color: black;
  
}

.col-75 {
  text-align: right;
  color: black;
}
  }


mark {
  background-color: yellow;
  color: black;
  }

  * {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 100%;
  padding-bottom: 0em;
  border: 0px;
  resize: vertical;
  font-family: 'ABC Helveesti Trial';
  font-size: 1em;
  outline: none;
  background-color: none;
}

label {
  display: inline-block;
  outline: none;
}

input[type=submit] {
  background-color:none;
  font-size: 1em;
  font-family: 'Arial Rounded MT Bold';
  border: none;
  padding:0em;
  cursor: pointer;
  float: right;
  outline: none;
}

input[type=submit]:hover {
  background-color:none;
  outline: none;
  padding:0em;
}



/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}
  

  @media (max-width: 48em) {
.column {
  float: left;
  height: calc(8em + 5vw);
  width: 100%;}

.row2 {
  padding-top: .67em;
  padding-right: .67em;
  margin-left: 2vw;
  margin-right: 2vw;

  background-color:none;}

 .col-25 {
  text-align: right;
  color: black;
  font-size: 1.25em;
  margin: 0em;
  padding:0em;}

.col-75 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
   background-color:none;}

.left2 {
width: calc(8em + 5vw);
  height: 2em;}
h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 2vw;
  margin-right: 2vw;
  background-color: none;
  padding:2vw;
}

        }


 @media (min-width: 48em) {
.column {
  float: left;
  background-color: none;
}

.row2 {
  padding-top: .67em;
  padding-right: .67em;
  margin-left: 25vw;
  margin-right: 2vw;
  background-color: none;}
  
h3 {
  margin-top:1.5em;
  margin-left:24.67vw;
  margin-right:2vw;
  background-color: none;
  padding: .67vw;
  font-size:1.25em;
}

      }

  @media (min-width: 70em) {
.column {
  float: left;
  height: 2em;
  margin-top: 3em;}

  .row2 {
  padding-top: .67em;
  padding-right: .67em;
  margin-left: 25vw;
  margin-right: 2vw;
  background-color:none;}
  


h3 {
  font-size:1.25em;
  margin-top:1.5em;
  margin-left:25vw;
  margin-right:2vw;
  background-color: none;
  padding:.67vw;
}
      }

@media (max-width: 33em) {
     
.column {
  float: left;
  height: 8em;
}

.row2 {
  padding-top: .67em;
  padding-right: .67em;
  margin-left: 5vw;
  margin-right:5vw;}

 .col-25 {
  text-align: right;
  color: black;
  font-size: 1.25em;
  margin: 0em;
  padding:0em;}

.col-75 {
  text-align: right;
  color: black;
  margin: 0em;
  padding:0em;
  font-size: 1.25em;
  background-color:none;}       


h3 {
  margin-top: 4.8em;
  font-size:1.25em;
  margin-left: 5vw;
  margin-right: 5vw;
  padding:2vw;}
  }
</style>