<template>

<layout>
<div class="container">
	<div class="left">
		<div class="item item1">
			<input class="native-hidden" type="checkbox"/>
		</div>
		<div class="item item3">
			<div>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">LIBREVILLE (ROUGH MIX)</a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">EKWEGHELE</a><br>
				<audio id="nyan" src="https://designshack.net/tutorialexamples/html5-audio-player/media/evidence-song.mp3" preload="metadata" type="audio/mpeg">
				Your browser does not support the audio element. </audio>
				<a class="btn" id="nyan-btn">NEW CASINO</a><br>
			</div>
			<div class="item item5">
			</div>
		</div>
	</div>
	<div class="right">
		<div class="item item2">
			<h2 style="margin-bottom:-.67em; margin-top:0em;">"STAND UP FOR YOUR RIGHTS" LP</h2>
			<h2 style="margin-bottom:-.67em;">FEEL IT</h2>
			<h2 style="margin-bottom:-.67em;">CHARLIZ AG</h2>
			<h2 style="margin-bottom:-.67em;">SOUTH AFRICA, '89</h2>
			<h2 style="margin-bottom:0em;">VINYL VG+ SLEEVE VG</h2>
		</div>
		<div class="item item4" style="font-family:ABC Helveesti Trial;">
			<p>
				 A sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness.
			</p>
			<p>
				Death, drug abuse, politics and religion, usually in a poign pA sentimental ballad is an emotional style of music that often deals with romantic and intimate relationships, and to a lesser extent, war (protest songs), loneliness, death, drug abuse, politics and religion..
			</p>
			<p>
				 Usually in a poignant but solemn manner.
			</p>
			<p>
				Ballads are generally melodic enough to get the listener's attention but solemn manner. Ballads are generally melodic enough to get the listener's attention.
			</p>
		</div>
		<div class="item item6">
			<div>
				<h12 class style="font-size:1.67em; line-height:1.5;">139€</h12><br>
				<input type="submit" style="border-radius: 25px; padding:.34em; padding-right:.8em; padding-left:.8em;" value="ADD TO CART">
			</div>
			<section id="accordion" style="margin-top:.67em;">
			<div>
				<input type="checkbox" id="check-1"/>
				<label for="check-1" style="padding-bottom:0.67em;">CONDITIONS</label>
				<article>
				<p style="margin-bottom:.67em;font-family:ABC Helveesti Trial;line-height:1.125;">
					Hope that this place becomes somewhere fun on the web. I'll be filing it with all sorts of records; the kind you like. All styles respected, but the stock is heavily weighted towards the lesser-known. It seems there is no end to the pool of '80s records. <br>
					<br>
					 In recent years, I'm leaning more and more towards do-it-yourself. Be it pop music, tropical, boogie, etc. so long as it hits right.
				</p>
				</article>
			</div>
			</section>
			<section id="accordion">
			<div>
				<input type="checkbox" id="check-8"/>
				<label for="check-8" style="padding-bottom:0.67em;">SHIPPING INFO</label>
				<article>
				<p style="font-family:ABC Helveesti Trial;">
					Pricing is a good topic. Everything considered (rarity, hype, condition, and the music itself), the pricing also reflects the time spent chasing down these records. Also included in the price is the number of shitty records I've bought in the gambling process of "discovering" something unknown.<br>
					<br>
					 If the record is listed on discogs, I list cheaper. If there are no other copies available online, I'll try to find a price where it can sell for more in the future.<br>
					<br>
				</p>
				</article>
			</div>
			</section>
		</div>
	</div>
</div>
</div>
<row3>MORE GOOD RECORDS</row3>
<nav>
<div class="flex-container">
<div class="flex-item-left">
	<div class="flex-container3">
		<div class="flex-item-left3">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897451/z9_c9xmnc.jpg"/>
			</g-link>
		</div>
		<div class="flex-item-right3">
			<h5 style="margin-bottom:.34em">"I KNOW YOU FEEL IT" LP</h5>
			<h5>KUMASI</h5>
		</div>
	</div>
</div>
<div class="flex-item-right">
	<div class="flex-container3">
		<div class="flex-item-left3">
			<g-link to="/product/">
			<g-image src="https://res.cloudinary.com/winenot/image/upload/v1601897448/p1_jy7ug9.png"/>
			</g-link>
		</div>
		<div class="flex-item-right3">
			<h5 style="margin-bottom:.34em">TENDER LOVER 7"</h5>
			<h5>EDDY ALIMANTE</h5>
		</div>
	</div>
</div>
</div>
</div>
</nav>
</layout>
</template>




<style scoped>
.flex-container3{
    display:flex;
    flex-direction:column;
    text-align:left
}
.flex-item-left3{
    background-color:none;
    flex:50%
}
.flex-item-right3{
    background-color:none;
    padding-left:.67em;
    text-align:left;
    flex:50%
}
@media (max-width:48em){
    .flex-container3{
        flex-direction:row
    }
}
@media (max-width:48em){
    img {width: 100%;}
    nav{
        background-color:none;
        margin-left:5vw;
        margin-right:5vw
    }
    .flex-item-left3{
        background-color:none;
        padding:2vw;
        flex:50%
    }
    .flex-item-right3{
        background-color:none;
        padding:2vw;
        font-size:.67em;
        text-align:left;
        flex:50%
    }
    .flex-container{
        background-color:none;
        margin-bottom:1.67em
    }
    h5{
        font-size:1.25em;
        margin:auto
    }
    row3{
        background-color:#ff0;
        border-radius:25px;
        padding:.34em;
        width:8em;
        display:block;
        margin:auto;
        text-align:center;
        font-size:1.34em;
        transform:rotate(-20deg)
    }
}
@media (min-width:48em){
    img {width: 100%;}
    nav{
        width:0;
        margin-left:12vw;
        background-color:none;
    }
    .flex-container{
        background-color:none;
        border-radius:0;
        width:45vw;
        margin-bottom:6em
    }
    .flex-container3{
        display:contents;
        background-color:none;
        display:flex;
        flex-direction:column;
        text-align:left;
        padding:.34em
    }
    .flex-item-left3{
        background-color:none;
        flex:50%;
        width:30vw;
        margin-bottom:.34em
    }
    .flex-item-right3{
        background-color:none;
        width: 100%;
        font-size:.8em;
        text-align:left;
        flex:50%
    }
    h5{
        font-size:1em;
        margin:auto
    }
    row3{
        background-color:#ff0;
        border-radius:25px;
        padding:.34em;
        width:8em;
        display:block;
        margin-left:calc(57vw + 1em);
        text-align:center;
        font-size:1.34em;
        transform:rotate(-20deg)
    }
}
@media (max-width:33em){
    p{
        background-color:none
    }
    input{
        background-color:red;
        font-size:1.34em;
        font-family:Arial Rounded MT Bold;
        border:0;
        left:0
    }
    .container{
        background:0 0;
        margin-bottom:4em
    }
    .item{
        margin-bottom:0;
        text-align:left;
        background:0 0;
        margin-bottom:0
    }
    .btn{
        width:90vw;
        background-color:none;
        border-radius:25px;
        padding-right:.67em;
        padding-left:.67em;
        margin-right:2.67vw;
        margin-bottom:.34em
    }
    .item2{
        margin-top:5vw;
        background-color:none
    }
    .left,.right{
        display:contents
    }
    .item1,.item2{
        order:1
    }
    .item4,.item6{
        order:2
    }
    .item3,.item5{
        order:3
    }
    row3{
        margin-left:30%
    }
}
@media (max-width:48em){
    input{
        background-color:red;
        font-size:1.34em;
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:90vw;
        height:90vw;
        margin-left:0;
        margin-left:0;
        outline:0
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    p{
        background-color:none;
        line-height:1.125;
        font-size:1.34em
    }
    .checkbox{
        background-color:none
    }
    #accordion input{
        display:none
    }
    #accordion label{
        cursor:pointer;
        display:block;
        background:0 0;
        font-size:1.34em
    }
    #accordion input:checked+label{
        background:0 0;
        text-align:left
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        width:90vw;
        height:0;
        overflow:hidden;
        z-index:10;
        text-align:left
    }
    #accordion article p{
        font-size:1.125em;
        line-height:1.125;
        padding-right:1em;
        padding-left:1em;
        padding-top:1em;
        padding-bottom:.5em;
        text-align:left
    }
    #accordion input:checked~article{
        height:auto;
        box-shadow:0 6px 6vw 1vw #000;
        margin-bottom:1.67em;
        margin-left:0;
        text-align:left
    }
}
.btn{
    cursor:pointer;
    display:inline-block;
    text-align:right;
    margin-right:0;
    padding:0;
    margin-bottom:.34em
}
.container{
    margin-top:6em;
    margin-left:5vw;
    margin-right:5vw;
    margin-bottom:3em;
    width:90vw;
    background-color:none
}
.item{
    margin-bottom:0;
    text-align:left;
    background:0 0
}
.item1{
    padding-bottom:0;
    margin-top:-.2em;
    margin-bottom:0
}
.item2{
    margin-top:.67em;
    font-size:1.125em;
    background-color:none
}
h2{
    line-height:1
}
.item3{
    font-size:1.34em;
    text-align:right;
    line-height:1.34em;
    margin-bottom:1em;
    margin-right:0;
    background-color:none
}
.item4{
    margin-top:1em;
    margin-bottom:1em;
    background-color:none
}
.item6{
    background-color:none;
    margin-top:-.34em
}
.left{
    opacity:100%
}
.left,.right{
    display:contents
}
.item1,.item2{
    order:1
}
.item4,.item5{
    order:2
}
.item3,.item6{
    order:3
}
@media (min-width:48em){
    input{
        background-color:red;
        font-size:1.67em;
        font-family:Arial Rounded MT Bold;
        border:0;
        margin-left:-.8em
    }
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:30vw;
        height:30vw;
        outline:0
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    .btn{
        font-size:1em;
        cursor:pointer;
        display:inline-block;
        text-align:right;
        margin-bottom:.34em
    }
    .left,.right{
        display:inline-block;
        vertical-align:top
    }
    .item1{
        margin-bottom:1em;
        margin-left:1.34em
    }
    .item2{
        margin-bottom:.67em;
        width:40.4vw;
        font-size:1em;
        background-color:none
    }
    .item3{
        text-align:right;
        background-color:none
    }
    .item4{
        margin-bottom:1.34em;
        font-size:1em;
        line-height:1.125;
        background-color:none
    }
    p{
        background-color:none;
        font-size:1.34em
    }
    .container{
        display:block;
        background-color:none;
        margin-top:2.34em;
        margin-left:25vw;
        margin-bottom:6em
    }
    .left{
        width:30vw;
        margin-right:1em;
        background-color:none
    }
    .item2{
        margin-top:0;
        font-size:1.125em;
        margin-right:7vw;
        line-height:1
    }
    .right{
        width:45%;
        background-color:none
    }
    #accordion input{
        display:none
    }
    #accordion label{
        cursor:pointer;
        display:block;
        background:0 0;
        font-size:1.34em
    }
    #accordion input:checked+label{
        background:0 0;
        text-align:left
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        height:0;
        overflow:hidden;
        margin-left:-16vw;
        z-index:10;
        text-align:left
    }
    #accordion article p{
        font-size:1.em;
        padding-right:.5em;
        padding-left:1em;
        padding-top:1em;
        padding-bottom:.5em;
        text-align:left
    }
    #accordion input:checked~article{
        box-shadow:0 6px 6vw 1vw #000;
        height:auto;
        margin-bottom:3em;
        text-align:left
    }
}
@media (min-width:70em){
    input[type=checkbox]{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897475/hrb10_cxjt6q.jpg);
        display:block;
        width:30vw;
        height:30vw;
        outline:0
    }
    .left,.right{
        display:inline-block;
        vertical-align:top
    }
    .container{
        display:block;
        margin-left:25vw
    }
    .left{
        width:30vw;
        margin-right:1.34em;
        max-width:450px;
        background-color:none
    }
    .right{
        width:46%;
        background-color:none
    }
    .item1{
        margin-left:1.34em
    }
    .item2{
        font-size:1.125em;
        margin-bottom:1em;
        width:41.4vw;
        font-style:normal;
        background-color:none
    }
    .item3{
        font-size:1.34em;
        line-height:1.34;
        text-align:right;
        background-color:none;
        margin-right:3ev
    }
    .item4{
        margin-bottom:1.5em;
        margin-right:0;
        background-color:none
    }
    p{
        background-color:none
    }
    .btn{
        cursor:pointer;
        display:inline-block;
        text-align:right;
        margin-bottom:.34em
    }
    #accordion1 input{
        display:none
    }
    #accordion1 label{
        cursor:pointer;
        display:block;
        padding:.1725em 0;
        font-size:1.34em;
        background:0 0
    }
    #accordion1 input:checked+label{
        background:0 0;
        font-size:1.25em;
        margin-bottom:0
    }
    #accordion1 article{
        background:#f5f5f5;
        height:0;
        overflow:hidden;
        z-index:10
    }
    #accordion1 article p{
        padding:1em
    }
    #accordion1 input:checked~article{
        height:auto;
        margin-bottom:.125em
    }
    input[type=checkbox]:checked{
        content:url(https://res.cloudinary.com/winenot/image/upload/v1601897502/hrb11_og1zp4.jpg)
    }
    .native-hidden{
        -webkit-appearance:none;
        -moz-appearance:none;
        appearance:none
    }
    #accordion article{
        background:silver;
        border-radius:25px;
        height:0;
        overflow:hidden;
        margin-left:0;
        z-index:10;
        text-align:left
    }
}
@media (max-width:33em){
    nav{
        background-color:none;
        margin-left:2vw;
        margin-right:2vw
    }
    .flex-container{
        background-color:none;
        margin-bottom:1.67em
    }
    .flex-container3{
        display:flex;
        text-align:left
    }
    .flex-item-left3{
        background-color:none;
        flex:50%
    }
    h5{
        font-size:1.25em;
        margin:auto
    }
    .flex-item-right3{
        background-color:none;
        padding:2vw;
        font-size:.67em;
        text-align:left;
        flex:50%
    }
    row3{
        display:block;
        margin-left:auto;
        text-align:center;
        margin-bottom:0
    }
}
.pointer {cursor: pointer;}
</style>