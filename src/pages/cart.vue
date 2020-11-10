<template>
<layout>
<h3 style="font-family:ABC Helveesti Trial;">A frattura del pene o peniena, anche denominata sindrome del chiodo rotto, è un raro trauma del pene che consiste nell'improvvisa e dolorosa rottura della tonaca albuginea dei corpi cavernosi, dovuta a un colpo violento verificatosi durante l'erezione.<br>
<br>
Traumi simili, se avvenuti a pene flaccido ad esempio durante l'attività sportiva o per l'utilizzo di armi da fuoco, non vengono invece definiti fratture, ma semplici traumi penieni.</h3>
<div class="row">
	<div class="column left">
		<g-image src="https://res.cloudinary.com/samtech/image/upload/v1596047371/hrb7.jpg"/>
	</div>
	<div class="column middle">
		<h5 style="margin-top:.34em;">"STAND UP FOR YOUR RIGHTS" LP<br>
		 FEEL IT<br>
		 GUAVO LTD.<br>
		 SOUTH AFRICA, '89 <br>
		 VINYL VG+ SLEEVE VG- <br>
		</h5>
	</div>
	<div class="column right">
		<h4 style="margin-top:.34em;font-weight: normal;">170€</h4>
		<hi>REMOVE</hi>
	</div>
</div>
<div class="row">
	<div class="column left">
		<g-image src="https://res.cloudinary.com/samtech/image/upload/v1596047538/hrb10.jpg"/>
	</div>
	<div class="column middle">
		<h5 style="margin-top:.34em;">"SUN TAN CLUB" LP<br>
		 FOR LIGHT TANNING<br>
		 ESTAZ<br>
		 JAPAN, '86 <br>
		 VINYL VG+ SLEEVE VG<br>
		</h5>
	</div>
	<div class="column right">
		<h4 style="margin-top:.34em;font-weight: normal;">199€</h4>
		<hi>REMOVE</hi>
	</div>
</div>
<dd>
<div class="row1">
	<div class="column left1">
	</div>
	<div class="column middle1">
		<h4>SUBTOTAL</h4>
	</div>
	<div class="column right1">
		<h4>308€</h4>
	</div>
</div>
<div class="row1">
	<div class="column left1">
	</div>
	<div class="column middle1">
		<h4>SHIPPING</h4>
	</div>
	<div class="column right1">
		<h4>12€</h4>
	</div>
</div>
<div class="row1">
	<div class="column left1">
	</div>
	<div class="column middle1">
		<h4>TOTAL</h4>
	</div>
	<div class="column right1">
		<h4>320€</h4>
	</div>
</div>
</dd>
<row3>SHIPPING ADDRESS</row3>
<form action="/action_page.php">
	<div class="row2">
		<div class="col-25">
			<label for="name">NAME</label>
		</div>
		<div class="col-75">
			<input type="text" id="name" name="name" style="background-color:whitesmoke;border-radius: 25px; padding:.34em;padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="address1">STREET ADDRESS #1</label>
		</div>
		<div class="col-75">
			<input type="text" id="address1" name="address1" style="background-color:whitesmoke;border-radius: 25px; padding:.34em;padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="address2">STREET ADDRESS #2</label>
		</div>
		<div class="col-75">
			<input type="text" id="address2" name="address2" style="background-color:whitesmoke;border-radius: 25px; padding:.34em;padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="town">TOWN</label>
		</div>
		<div class="col-75">
			<input type="text" id="town" name="town" style="background-color:whitesmoke;border-radius: 25px; padding:.34em;padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="postcde">POST CODE</label>
		</div>
		<div class="col-75">
			<input type="text" id="postcode" name="postcode" style="background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="state">STATE/REGION</label>
		</div>
		<div class="col-75">
			<input type="text" id="state" name="state" style="background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="country">COUNTRY</label>
		</div>
		<div class="col-75">
			<input type="text" id="country" name="country" style="background-color:whitesmoke;border-radius: 25px; padding:.34em; padding-left:1.5em;" placeholder="">
		</div>
	</div>
	<div class="row2">
		<div class="col-25">
			<label for="subject">ADDITIONAL COMMENT</label>
		</div>
		<div class="col-75">
			<textarea id="subject" name="subject" placeholder="" style="background-color:whitesmoke; height:3em;border-radius: 25px; padding:.34em; padding-left:1.5em;"></textarea>
		</div>
	</div>
	<div class="row2" style="margin-bottom:8em;">
		<div class="col-25" style="text-align:center; margin-right:0em; margin-bottom:8em;">
			<input type="submit" style="background-color:green;border-radius: 25px; padding:.34em; padding-right:.67em; padding-left:.67em;" value="CHECK OUT">
		</div>
	</div>
</form>
</layout>
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


<style>@media (min-width:48em) {
	.left,.right {
		display:inline-block;
		vertical-align:top;
	}
	.row {
		margin-right:4vw;
	}
	.col-25 {
		text-align:right;
		color:black;
		font-size:1.25em;
		border-radius:25px;
		margin-right:1em;
		margin-bottom:.34em;
	}
	.col-75 {
		text-align:right;
		color:black;
		font-size:1.125em;
		border-radius:25px;
		margin-bottom:.34em;
	}
}
@media (min-width:70em) {
	.left,.right {
		display:inline-block;
		vertical-align:top;
	}
	.row {
		margin-right:7.34vw;
	}
	.col-25 {
		text-align:right;
		color:black;
		border-radius:25px;
		margin-right:1em;
		margin-bottom:.34em;
		background-color:none;
	}
	.col-75 {
		text-align:right;
		border-radius:25px;
		margin-bottom:.34em;
	}
}
mark {
	background-color:yellow;
	color:black;
}
* {
	box-sizing:border-box;
}
input[type=text],select,textarea {
	width:100%;
	padding-bottom:0em;
	border:0px;
	resize:vertical;
	font-family:'ABC Helveesti Trial';
	font-size:1em;
	outline:none;
}
label {
	display:inline-block;
	outline:none;
}
input[type=submit] {
	background-color:none;
	font-size:1em;
	font-family:'Arial Rounded MT Bold';
	border:none;
	padding:0em;
	cursor:pointer;
	float:right;
	outline:none;
}
input[type=submit]:hover {
	background-color:none;
	outline:none;
	padding: 0em;
}
/* Clear floats after the columns */
.row:after {
	content:"";
	display:table;
	clear:both;
}
@media (max-width:48em) {
	.column {
		float:left;
		background-color:none;
	}
	.row {
		margin-left:2vw;
		margin-right:2vw;
		margin-bottom:1em;
		align-content:center;
		background-color:none;
	}
	.row1 {
		margin-left:2vw;
		margin-right:2vw;
		height:1.67em;
		align-content:center;
		width:9vw;
		background-color:none;
	}
	.row2 {
		padding-top:.67em;
		padding-right:0em;
		margin-left:5vw;
		margin-right:5vw;
		background-color:none;
		border-radius:25px;
	}
	row3 {
		display:block;
		margin:auto;
		text-align:center;
		margin-bottom:1.67em;
		font-size:1.34em;
	}
	dd {
		background-color:none;
		border-radius:25px;
		margin-left:29vw;
		margin-right:2vw;
		margin-bottom:3em;
	}
	.col-25 {
		text-align:left;
		color:black;
		font-size:1.25em;
		margin-left:1em;
		margin-bottom:.34em;
		border-radius:25px;
		background-color:none;
	}
	.col-75 {
		text-align:right;
		color:black;
		margin-bottom:.34em;
		padding:0em;
		font-size:1.125em;
		border-radius:25px;
		background-color:none;
	}
	.right {
		position:absolute;
		right:5vw;
		margin-top:-.67em;
		width:3em;
		height:2em;
		background-color:none;
	}
	.right1 {
		position:absolute;
		right:5vw;
		width:5em;
		height:2em;
		background-color:none;
	}
	.middle {
		width:45vw;
		margin-top:-.67em;
		background-color:none;
	}
	.middle1 {
		position:absolute;
		height:2em;
		background-color:none;
	}
	.left {
		margin-right:2vw;
		width:27vw;
	}
	.left1 {
		height:2em;
		margin-right:2vw;
		background-color:none;
	}
	.left2 {
		width:calc(8em+5vw);
		height:2em;
	}
	hi {
		z-index:-2;
		background-color:yellow;
		position:absolute;
		right:0vw;
		font-size:1.25em;
		margin-top:.34em;
		margin-right:-.5em;
		border-radius:25px;
		padding:.5em;
	}
	h3 {
		margin-left:5vw;
		margin-right:5vw;
		font-size:1.25em;
		margin-top:4.8em;
		line-height:1.125em;
		text-align:left;
		margin-bottom:3em;
		background-color:none;
	}
	h4 {
		margin:0em;
	}
	h5 {
		font-size:1.25em;
	}
}
@media (min-width:48em) {
	.column {
		float:left;
	}
	.row {
		margin-left:25vw;
		margin-top:.34em;
		margin-right:12vw;
		margin-bottom:1.34em;
		align-content:center;
		background-color:none;
	}
	.row1 {
		margin-left:0vw;
		margin-right:0vw;
		height:2em;
		align-content:center;
		background-color:none;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
		margin-left:25vw;
		margin-right:2vw;
		background-color:none;
	}
	row3 {
		display:block;
		margin-left:45vw;
		margin-right:23vw;
		text-align:center;
		font-size:1.5em;
	}
	dd {
		background-color:none;
		border-radius:25px;
		margin-left:50vw;
		margin-right:3vw;
		padding:0em;
		margin-bottom:3em;
		margin-top:.67em;
	}
	.right {
		position:absolute;
		right:5vw;
		width:5em;
		height:4em;
		background-color:none;
	}
	.right1 {
		position:absolute;
		right:5vw;
		width:5em;
		height:2em;
	}
	hi {
		z-index:-2;
		background-color:yellow;
		position:absolute;
		right:0vw;
		font-size:1.25em;
		margin-top:.34em;
		margin-right:-.34em;
		border-radius:25px;
		padding:.34em;
	}
	.middle {
		width:34vw;
		height:24vw;
		background-color:none;
	}
	.middle1 {
		height:2em;
		margin-left:1vw;
		background-color:none;
	}
	.left {
		width:24vw;
		height:24vw;
		margin-right:2vw;
		padding:0em;
	}
	.left1 {
		width:0vw;
		height:2em;
	}
	h3 {
		margin-top:1.8em;
		margin-left:24.67vw;
		margin-right:5vw;
		line-height:1.125;
		background-color:none;
		font-size:1.25em;
		text-align:left;
	}
	h4 {
		font-size:1.34em;
		margin:0em;
	}
	h5 {
		font-size:1.34em;
	}
	hi {
		font-size:1.34em;
	}
}
@media (min-width:70em) {
	.column {
		float:left;
		height:2em;
	}
	.row {
		background-color:none;
		margin-left:25vw;
		margin-bottom:1.67em;
	}
	.row1 {
		margin-right:2vw;
		align-content:center;
		background-color:none;
	}
	.row2 {
		padding-top:.67em;
		padding-right:.67em;
		margin-left:25vw;
		margin-right:2vw;
		background-color:none;
	}
	.right {
		position:absolute;
		right:5vw;
		width:5em;
		background-color:none;
	}
	.right1 {
		position:absolute;
		right:5vw;
		width:5em;
		font-size:1.125em;
	}
	hi {
		background-color:yellow;
		position:absolute;
		font-size:1.67em;
		margin-top:.34em;
		margin-right:-.34em;
		border-radius:25px;
		padding:.34em;
	}
	h4 {
		font-size:1.67em;
	}
	h5 {
		font-size:1.67em;
	}
	.middle {
		width:32vw;
		background-color:none;
	}
	.middle1 {
		height:2em;
		margin-left:.5vw;
		background-color:none;
	}
	dd {
		background-color:none;
		margin-left:49.5vw;
		margin-right:3.67vw;
		margin-bottom:3em;
		margin-top:1.67em;
	}
	.left {
		width:24vw;
		height:24vw;
		margin-right:1vw;
		padding:0em;
	}
	.left1 {
		width:0vw;
		height:2em;
	}
	h3 {
		margin-bottom:1.67em;
		margin-left:25vw;
		margin-right:5vw;
		line-height:1.125;
		background-color:none;
	}
}
@media (max-width:33em) {
	.column {
		float:left;
		height:25.75vw;
		background-color:none;
	}
	.row {
		margin-left:3vw;
		margin-right:3vw;
		margin-bottom:1em;
		height:24vw;
		background-color:none;
	}
	.row1 {
		margin-left:2vw;
		margin-right:2vw;
		width:9vw;
		background-color:none;
	}
	.row2 {
		margin-left:5vw;
		margin-right:5vw;
		background-color:none;
	}
	row3 {
		display:block;
		margin:auto;
		margin-bottom:1.67em;
		font-size:1.34em;
	}
	.col-25 {
		color:black;
		font-size:1.25em;
		margin-left:1.25em;
		margin-bottom:.125em;
		background-color:none;
	}
	.col-75 {
		margin-top:0em;
		margin-bottom:.34em;
		padding:0em;
		font-size:1.25em;
		background-color:none;
	}
	dd {
		background-color:none;
		border-radius:25px;
		margin-left:26vw;
		margin-top:1.67em;
		width:72vw;
	}
	.right {
		background-color:none;
		margin-top:-.5em;
		text-align:right;
		width:3em;
	}
	.right1 {
		text-align:right;
		background-color:none;
		position:absolute;
		right:5vw;
	}
	.middle {
		width:46vw;
		margin-left:0em;
		margin-top:-.5em;
		background-color:none;
	}
	.middle1 {
		text-align:left;
		position:absolute;
		left:29vw;
		background-color:none;
	}
	.left {
		width:24vw;
	}
	.left1 {
		width:24vw;
		height:0;
		margin-right:2vw;
	}
	h3 {
		font-size:1.125em;
		line-height:1.125;
		margin-top:5.34em;
		background-color:none;
	}
	h4 {
		font-size:1.25em;
		line-height:1;
		margin:0em;
		background-color:none;
	}
	h5 {
		font-size:1.125em;
		line-height:1;
		background-color:none;
	}
	hi {
		font-size:1.125em;
		margin-top: .34em;
	}
}
</style>