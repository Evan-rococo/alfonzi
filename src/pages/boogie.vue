<template>
<div> 
	  <div class="overlay"></div>
    
  <Layout>
	    
    	<section class="products">
        <genre style="position:fixed;">BOOGIE</genre>
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876491/p1.png" width="450em;" height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">"ICH TRÄUME SO LEISE VON DIR" LP</p>
				<p>BECKER, STEGMANN, LASKER-SCHULER</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028675/p2.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">MR. MAC 12"</p>
				<p>STEVE WILLIAMS</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876539/p3.png" width=450em; height="450em;"/>
    </g-link>
			</div>
	<div class="product-info">
				<p style="margin-bottom: .34em;">SKETCHES OF ANDERLAND 7"</p>
				<p>ANGELO VANOTTI</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028557/p4.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">"I KNOW YOU FEEL IT" LP</p>
				<p>KUMASI</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876770/p5.png" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">S/T LP</p>
				<p>PUZZLE</p>
			</div>
		</div>

		<div class="product-card">
			<div class="product-image">
			 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028853/w6.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">TENDER LOVER 7"</p>
				<p>EDDY ALIMANTE</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028675/p2.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">UNLICENSED DEMO 12"</p>
				<p>WITHHELD</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876539/p3.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">MY NAME IS BOND 12"</p>
				<p>BEAT CONTROL</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876491/p1.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">FEELING NICE 12"</p>
				<p>JAM-MASTER KING</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028557/p4.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">"JAZZ MAIDEN" EP</p>
				<p>ACCURA</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876539/p3.png" width="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">"BÖHÖBÉ SPIRITS MUSIC" LP</p>
				<p>NORBERTO DO NÖAH</p>
			</div>
		</div>
		
		<div class="product-card">
			<div class="product-image">
				 <g-link to="/product/">
    <g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028231/g1.jpg" width=450em; height="450em;"/>
    </g-link>
			</div>
			<div class="product-info">
				<p style="margin-bottom: .34em;">TENESSEE STUD 12"</p>
				<p>NEVER WAS A HORSE LIKE</p>
			</div>
		</div>
	
	</section>
	
  </Layout>
</div>
</template>

<script>
 export default {
      
    }
</script>

<style scoped>
/* @import url('../reset.css'); */
/* Product Layout */

.product-filter {
	display: flex;
	}

.sort {
	display: flex;
	align-self: flex-end;
	}

.collection-sort {
 	display: flex;
 	flex-direction: column;
 	}

.collection-sort:first-child {
	padding-right: 0px;
}

label {
	color: orange;
}

.products {
	display: flex;
	flex-wrap: wrap;
	margin-top:6em;
	margin-left:5vw;
	margin-bottom: 8em;
	width:98vw;
	background-color:none;
	
}

.product-card {
	display: flex;
	flex-direction: column;
	flex: 1 30%;
	padding-left: 0vw;
	padding-right: 0vw;
}

.product-image img {
	width: 100%;
}

.product-info {
	margin-top: auto;
	padding-top: .67em;
	padding-bottom: 1em;
	text-align: right;
	font-size: calc(.34em + 1.34vw);
}


@media ( max-width: 48em ) {
	genre {
    background-color: none;
    font-size: 1.34em;
    padding: .34em;
    padding-left:.67em;
    padding-right:.67em;
    border-radius: 25px;
    margin-top:-1.8em;
    right:3vw;

  }
	.product-card {
	flex: 1 46%;
	}
	
	.products .product-card:first-child, 
	.products .product-card:nth-child(2) {
	flex: 2 90%;
	}

	.overlay {
        position: absolute;
        top: 0;
        left: 0;
        height: 1%;
        width: 1%;
        z-index: 10;
      }

    .modal {
        width: 54vw;
        position: fixed;
        top: 30%;
        left: 20%;
        text-align: center;
        z-index: 11;
      }

	.header a {
    float: right;
    display: block;
    align-items: center;
    background-color:none;
    margin-right: .5em;
    margin-top:0em;
    }

    .header {
    float: right;
    display: block;
    position: fixed;
    left: 0;
    top: 0;
    }
    
    .header-right {
    margin-top:0.96em;
    font-size: 1.5em;
    position: relative;
    left: 0;
    top: 0;
    background-color:none;
  	}
}

@media ( min-width: 48em ) {
	
	h1 {
		margin-bottom: 0;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 2.34em;
	margin-left:25vw;
	width:75.67vw;
	flex: 1 36%;
   background-color:none;
	}

	.product-info {
	text-align: right;
	font-size: calc(.34em + .67vw);
}

  .product-card {
	flex: 1 46%;
  margin-right:3vw;
	}
	
	
	.product-filter {
		flex-direction: column;
	}
	
	.sort {
		align-self: flex-start;
	}

	 .overlay {
        position: absolute;
        top: 0;
        left: 0;
        height: 1%;
        width: 1%;
        z-index: 10;
      }
      .modal {
        width: 25vw;
        position: fixed;
        top: 30%;
        left: 48.34%;
        text-align: center;
        z-index: 11;
      }

	    .form.example input[type=text] {
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

.header-right {
  float: right;
  font-size: 2em;
  margin-right: 9vw;
  background-color: none;
  }
  	genre {
    background-color: none;
    font-size: 1.34em;
    padding: .34em;
    padding-left:.67em;
    padding-right:.67em;
    border-radius: 25px;
    margin-top:-3.34em;
    right:2vw;
  }

  }

@media screen and (max-width: 70em) {
    .header a {
    background-color: none;
    margin-left: .86vw;
    float: left;
    }

   .header {
    background-color:none;
    } 
    
  .header-right {
    float: fixed;
    background-color: none;
  }
}

  
@media screen and (max-width: 33em) {
	.product-card {
		flex: 2 100%;
    margin-left:0vw;}

  	genre {
    background-color: none;
    font-size: 1.34em;
    padding: .34em;
    padding-left:.67em;
    padding-right:.67em;
    border-radius: 25px;
    margin-top:-1.8em;
    right:2vw;
  }

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 6em;
	margin-left: 5vw;
  margin-right: 5vw;
	width:90vw;
	flex: 1 36%;
	}	

  .header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }

 .header {
  position: fixed;
  left: 0;
  top: 0;
} 
    
.header-right {
  float: left;
  margin-left:3em;
  margin-top:-1.5em;
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

/* Change background on mouse-over */
.navbar a:hover {
  color: red;
}
/* Main content */
.main {
  margin-top: 0px;}
.Sidebar {
  background:none; opacity: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: 0;
  margin-left: 8vw;
  font-size: 1.67em;
  width: 7em;
}
.Hamburger {
  position: fixed;
  margin-top: 3em;
  opacity: 0;
  z-index: 2;
  margin-left:2.5vw;
}

@media (max-width: 48em) {
  	.product-card {
		flex: 2 100%;
    margin-bottom: 1em;
    font-size: 2em;
	}

	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 6em;
	margin-left: 5vw;
  margin-right: 5vw;
	width:90vw;
	flex: 1 36%;
	}	

  .header a {
  float: right;
  display: block;
  text-align: right;
  margin-right: 1.67vw;
  position: relative;
  left: 0;
  top: 0;
  }
  .Sidebar {
    transform: translate3d(-100%, 0, 0);
    top: 3em;
    
  }
  .Hamburger {
    opacity: 1;
    margin-left:2.5vw;
    top: -2.2em;
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


@media (max-width: 70em) {
  .Sidebar {
  position: fixed;
  background:none;
  top: 3.6em;
  bottom: 0;
  left: 0;
  background:none;
  opacity: 100%;
  z-index: 0;
  margin-left: 2.34vw;
  width: 6em;
  }
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

  
   @media (max-width: 48em) {
     .Hamburger {
  margin-left: 2.34vw;
}
     
      .Sidebar {
      background:yellow;
      margin-left:-.0em;
      padding-left:.34em;
      padding-top: .5em;
      padding-bottom: .34em;
      padding-right: .34em;
      height: 12.67em;
      width: 7em;
        }
      }
 @media (min-width: 70em) {
 	.products {
	display: flex;
	flex-wrap: wrap;
	margin-top: 2.34em;
	margin-left:25vw;
	width:75.67vw;
	flex: 1 36%;
  background-color: none;
	}

	.product-info {
	text-align: right;
	font-size: 1em;
}

  .product-card {
	flex: 1 26%;
  margin-right:3vw;
	}
	
     .Sidebar {
  position: fixed;
  background:none;
  top: 3.6em;
  bottom: 0;
  left: 0;
  background:none;
  opacity: 100%;
  z-index: 0;
  margin-left: 7.34vw;
  width: 6em;
        }
      }
  #nav{
  display:none;
}

</style>