<template>
  <Layout>
        
  
  <div class="container">
  <div class="left">
    <div class="item item1">
      <h5 style="background-color:none;line-height:1.125em;font-family:ABC Helveesti Trial;">Welcome to the Frequently asked questions page. Here are the answers to them. In the chance that you have a question that is not frequently asked, please <mark><g-link to="/contact">gimme a holler over here.</g-link></mark><br></h5>
</div>
      
</div><div class="right">
    <div class="item item4">
      <section id="accordion">
			  <div>
				<input type="checkbox" id="check-5"/>
				<label for="check-5" style="padding-bottom:0.67em;">WHO ARE YOU?</label>
				<article>
					<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial;line-height:1.125;">I'm just a guy buying too many records. If not addiction, its gotta be defined as compulsion. My name is Evan Jordan. I'm an american guy, living in sweden. <br><br> I guess i've been collecting seriously for.. what year is it now? It's been almost 10 years now. I'd like to think i'm pretty knowledgable about all this stuff. Please drop me a line if you've got any questions, requests or just wanna chat. </p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-1" />
				<label for="check-1" style="padding-bottom:0.67em;">WHAT IS THIS PLACE ABOUT?</label>
				<article>
					<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial;line-height:1.125;">Hope that this place becomes somewhere fun on the web. I'll be filing it with all sorts of records; the kind you like. All styles respected, but the stock is heavily weighted towards the lesser-known. It seems there is no end to the pool of '80s records. <br><br> In recent years, I'm leaning more and more towards do-it-yourself. Be it pop music, tropical, boogie, etc. so long as it hits right.</p>
				</article>
			</div>
      </section>
			</div>
    <div class="item item3" style="padding-bottom:0.67em;">
      <section id="accordion">
			<div>
				<input type="checkbox" id="check-8" />
				<label for="check-8" style="padding-bottom:0.67em;">WHAT'S WITH THESE PRICES?</label>
				<article>
					<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial; line-height:1.125;">Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br><br>
          If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br><br>
          I agree there is a sizeable speculativity, but I want to err on being conservative in my pricing.</p>
				</article>
			</div>
		</section>


        <section id="accordion">
			<div>
				<input type="checkbox" id="check-3" />
				<label for="check-3" style="padding-bottom:0.67em;">HOW DO I PAY?</label>
				<article>
					<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial;line-height:1.125;">Payments can be made either by Paypal or, in the case of Swedish residents, Swish.</p>
				</article>
			</div>
			<div>
				<input type="checkbox" id="check-4" />
				<label for="check-4">WHAT CAN YOU TELL ME ABOUT SHIPPING?</label>
				<article>
					<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial;line-height:1.125">In your paypal payment, a tracking number will be added and can be searched <mark><g-link to="https://www.postnord.se/en/our-tools/track-and-trace2">right here.</g-link></mark> PostNord delivers within 5 working days in the EU and somewhere around 6-8 in North america and Asia.</p>
				</article>
			</div>
		</section>
        </div>
      </div>
    </div>
  </Layout>
</template>



<style scoped>

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


.left {
  width: 100%;
}

.right{
  width: 37%;}

  .item1 {
  padding-bottom: 1.67em;
}

@media (max-width: 33em) {
  .item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  }
  
.item1 {
  padding-bottom: .67em;
  margin-top:-1em;
}
  .left {
    opacity: 66%;
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
}
@media (max-width: 48em) {
  .container {
    margin-left:5vw;
    margin-right:5vw;
    margin-bottom:8em;
    margin-top: 6em;
    width: 90vw;
    background-color: none;
    }

.item {
  margin-bottom: 0em;
  text-align: left;
  background:none;
  }

.item1 {
  padding-bottom: .67em;
  margin-top:-2em;
}

.left {
  opacity: 100%;
  }

.right {
background-color: none;

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
}
   
@media (min-width: 48em){
  .left, .right{
    display: inline-block;
    vertical-align: top;
  }
  
  .container{
    display: block;
    margin-left: 25vw;
    background-color:none;
    margin-right:1vw;
  }

  .left{
    width: 45%;
    margin-right: 3vw;
    padding-top: 0em;
    background-color: none;
    }

  .right{
    width: 50%;
    margin-top: 1.8em;
    background-color: none;}

     #accordion input {
	display: none;
}
#accordion label {
	background:white;
	cursor: pointer;
	display: block;
	margin-bottom: .0;
	padding: .1725em 0em;
	z-index: 20;
  font-size: 1.34em;
  line-height: 1em;
  background:none;
  text-align: right;
}
#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.34em;
	margin-bottom: 0;
  text-align: right;
}
#accordion article {
	background: none;
	height:0px;
	overflow:hidden;
	z-index:10;
  text-align: right;
}
#accordion article p {
	padding: 1em;
  text-align: right;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	height: auto;
	margin-bottom: .125em;
  text-align: right;}
}

@media (min-width: 70em){
  .left, .right{
    display: inline-block;
    vertical-align: top;}
  
  .container{
    display: block;
    margin-left: 24.67vw;
    margin-right:2vw;}
    
  .left{
     width: 45%;
    margin-right: 2vw;}
  
  .right{
    width: 49%;
    margin-right: 2vw;}

}
.item2 {
  margin-bottom: 1.5em;
}
.item3 {
  line-height: 1em;
  background-color: none;
}

.btn{
   font-size: 1.25em;
   line-height: 1.5em;
   cursor:pointer;
   display:inline-block;
   text-align: right;
   }

   #accordion input {
	display: none;
}
#accordion label {
	background:white;
	
	cursor: pointer;
	display: block;
	margin-bottom: .0;
	padding: .1725em 0em;
	z-index: 20;
  font-size: 1.34em;
  line-height: 1em;
  background:none;
  text-align: left;
}
#accordion label:hover {
}

#accordion input:checked + label {
	background:none;
	font-size: 1.34em;
	margin-bottom: 0;
  text-align: left;
}
#accordion article {
	background: none;
	height:0px;
	overflow:hidden;
	z-index:10;
  text-align: left;
}
#accordion article p {
	padding: 1em;
  text-align: left;
}
#accordion input:checked article {
}
#accordion input:checked ~ article {
	height: auto;
	margin-bottom: .125em;
  text-align: left;
}

mark {
  background-color: yellow;
  }

  
</style>