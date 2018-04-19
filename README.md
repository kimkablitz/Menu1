# Menu1
code to menu in CSS
<!DOCTYPE html>

<head>
	<title>Kim Kablit'z Restaurant</title>
	<link href="https://fonts.googleapis.com/css?family=Prata" rel="stylesheet">
	<style>
	h1 {
		font-family: 'Prata', serif;
		color: #803500;
		font-size: 50px;
		text-align: center;
		margin:60px 0 0 0;

	}
	h2 {
		text-align: center;
		margin: 23px 0 70px 0;
		color: #cc5500
		;
	}
		body{
			font-family: helvetica,sans-serif;
			margin: 0 auto;
			max-width: 800px;
			background-color:#f5d6eb;
		}
		div {
			margin: 30px 0 0 0;
			height: 600px;
			background-size: cover;
			position: relative;
			border-radius: 12px;
		}
		p {
			background-color: black;
			color:white;
			background:-webkit-linear-gradient(bottom,purple,yellow);
			background: -moz-linear-gradient(bottom,purple,yellow);
			font-size: 18px;
			padding: 10px;
			text-align: justify;
			line-height: 28px;
			position: absolute;
			bottom: 0;
			margin: 0;
			height: 75px;
		}
		.first {
			background: url("https://i.imgur.com/HIhGaob.jpg");
			background-repeat: no-repeat;
			background-size: 800px;
		}
		.second {
			background: url("https://i.imgur.com/S4LsKYM.jpg");
		    background-repeat: no-repeat;
			background-size: 800px;
		}
		.third {
			background: url("https://i.imgur.com/l2AcU5S.jpg");
			background-repeat: no-repeat;
			background-size: 800px;
		}
		.price {
			float: right;
		}
		
	</style>
</head>
<body>
	<h1>Chef Kim's Specialty</h1>
	<h2>This week's Menu</h2>
	<div class="first">
		<p>Japanese Udon <span class="price">$11.99</span><br /><small>Chef's special Hokkaido recipe of Udon enhanced with Vietnamese secrect noodle soup base accent. Topped with premium seafoods, local organic produce and homemade batter</small></p>
	</div>
	<div class="second">
	    <p>Authentic Bavarian Schnitzel <span class="price">$21.99</span><br /><small>Solo travelling to Bavarian village where I met with native Bavarian Daniel Anselm. With a bit of the Kablitz family flavor</small></p>
	 </div>
	 <div class="third">
	 	<p>The Seattle's Eggsbenedicts <span class="price">$17.65</span><br /><small>Sunday's brunch perfect for two.Served in homemade sauce. Entree comes with honey toasts and complimentary coffee</small></p>
	 </div>


</body>
</html>
