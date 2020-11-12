<template>
<div class="pointer">
<div>
	<div class="overlay">
	</div>
	<layout>
	<section class="products">
	<genre style="position:fixed;">BOOGIE</genre>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897504/z8_v2hh9u.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"ICH TRÄUME SO LEISE VON DIR" LP
			<br>
				BECKER, STEGMANN, LASKER-SCHULER
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/samtech/image/upload/f_auto/q_auto/v1595876539/p3.png"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				MR. MAC 12"
			<br>
				STEVE WILLIAMS
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897501/z6_ffdulq.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				SKETCHES OF ANDERLAND 7"
			<br>
				ANGELO VANOTTI
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"I KNOW YOU FEEL IT" LP
			<br>
				KUMASI
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897497/hrb7_ixwoxu.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"STAND UP FOR YOUR RIGHTS" LP
			<br>
				FEEL IT
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897510/z5_lxwfqq.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				TENDER LOVER 7"
			<br>
				EDDY ALIMANTE
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897477/hrb19_maeaud.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"CELIAS" LP
			<br>
				SOLO & NAMANA
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897485/z3_jmlxdd.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				MY NAME IS BOND 12"
			<br>
				BEAT CONTROL
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897549/z2_cd3q6o.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				FEELING NICE 12"
			<br>
				JAM-MASTER KING
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/samtech/image/upload/v1596028557/p4.png"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"JAZZ MAIDEN" EP
			<br>
				ACCURA
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897499/hrb8_rsbwri.jpg"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				"BÖHÖBÉ SPIRITS MUSIC" LP
			<br>
				NORBERTO DO NÖAH
			</p>
		</div>
	</div>
	<div class="product-card">
		<div class="product-image">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897453/s3_pffkyo.jpg" width=450em; height="450em;"/>
			</g-link>
		</div>
		<div class="product-info">
			<p>
				U GOT THE CHARM 12"
			<br>
				AMBILEKA
			</p>
		</div>
	</div>
	</section>
	</layout>
</div>
</div>
</template>

<script>
 export default {
      
    }
</script>
<style scoped>
.products{
    display:flex;
    flex-wrap:wrap;
    margin-top:6em;
    margin-left:5vw;
    margin-bottom:3em;
    width:98vw;
    background-color:none;
}
.product-card{
    display:flex;
    flex-direction:column;
    flex:1 30%;
    padding-left:0;
    padding-right:0
}
.product-info{
	background-color: none;
    margin-top:auto;
    padding-bottom:1em;
    text-align:right;
    font-size:calc(.34em+1.34vw)
}
@media (max-width:48em){
	img {width: 100%;
		}
		
		.product-info{
    padding-bottom:1.67em;
	padding-top: .34em;
    text-align:right;
    font-size:calc(.34em+1.34vw)
}

	p {margin: 0em;
		line-height: 1.125;
		background-color: none;
	}

    genre{
        background-color:red;
        font-size:1.34em;
        padding:.34em;
        padding-left:.67em;
        padding-right:.67em;
        border-radius:25px;
        margin-top:-2.34em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 6vw 2vw #000
    }
    .product-card{
        flex:1 46%;
		background-color: none;
		
    }
    .products .product-card:first-child,.products .product-card:nth-child(2){
        flex:2 90%
    }
    .overlay{
        position:absolute;
        top:0;
        left:0;
        height:1%;
        width:1%;
        z-index:10
    }
}
@media (min-width:48em){
	img {width: 100%;}

	.product-info{
    padding-bottom:1em;
	padding-top: .34em;
    text-align:right;
    font-size:calc(.34em+1.34vw)}

	p {margin: 0em;
		line-height: 1.125;
		background-color: none;
		}

    genre{
        background-color:red;
        font-size:1.34em;
        padding:.34em;
        padding-left:.67em;
        padding-right:.67em;
        border-radius:25px;
        margin-top:-3em;
        right:3vw;
        transform:rotate(-20deg);
        box-shadow:0 0 6vw 2vw #000}

    h1{
        margin-bottom:0}

    .products{
        align-items:baseline;
        display:flex;
        flex-wrap:wrap;
        margin-top:2.34em;
        margin-left:25vw;
        width:74.2vw;
        flex:1 36%;
        margin-bottom:6em;
        background-color:none;}
   
    .product-card{
        flex:1 46%;
        margin-right:2.5vw
    }
    .overlay{
        position:absolute;
        top:0;
        left:0;
        height:1%;
        width:1%;
        z-index:10
    }
    genre{
        background-color:none;
        font-size:1.34em;
        padding:.34em;
        padding-left:.67em;
        padding-right:.67em;
        border-radius:25px;
        margin-top:-3.34em;
        right:2vw
    }
}
@media screen and (max-width:33em){
	.product-info{
    padding-bottom:1.67em;
	padding-top: .175em;
    text-align:right;
    font-size:calc(.34em+1.34vw)
}

	p {margin: 0em;
		line-height: 1.125;
		background-color: none;
	}

    .product-card{
        flex:2 100%;
		background-color:none;
		width: 90vw;
    }
	
    genre{
        background-color:none;
        font-size:1.34em;
        padding:.34em;
        padding-left:.67em;
        padding-right:.67em;
        border-radius:25px;
        margin-top:-2.34em;
        right:3vw;
		z-index: 3;
    }
    .products{
        display:flex;
        flex-wrap:wrap;
        margin-top:6em;
        margin-left:5vw;
        margin-right:5vw;
        width:90vw;
        flex:1 36%;
		background-color:none;
    }
}
@media (max-width:48em){
	
    .product-card{
        flex:2 100%;
        font-size:1.34em;
	    }

    .products{
        display:flex;
        flex-wrap:wrap;
        margin-top:6em;
        margin-left:5vw;
        margin-right:5vw;
        width:90vw;
        flex:1 36%
    }
}
@media (min-width:70em){
	img {max-width: 100%;}

		.product-info{
    padding-bottom:1.67em;
	padding-top: .175em;
    text-align:right;
    font-size:calc(.34em+1.34vw)
}

    .products{
        align-items:baseline;
        display:flex;
        flex-wrap:wrap;
        margin-top:2.34em;
        width:73vw;
        flex:1 36%;
        background-color:none
    }
    .product-card{
        flex:1 26%;
        margin-right:1.67vw
    }
}
.pointer {cursor: pointer;}
</style>