<!doctype html>
<html lang="en">
	<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
	
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.0.0/animate.min.css">
    <link href="https://fonts.googleapis.com/css?family=Amatic+SC|Didact+Gothic|VT323|Barrio&display=swap" rel="stylesheet">

    <link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" type="text/css" href="css/mobile.css">



    <title>p o r t f o l i o</title>

	</head>

	<body scroll="no" style="overflow: hidden">

	<div id="wrapper">
		<div id="entrada">
			<p class="typing"></p>
			<p class="tinyTyping"></p>
		</div>
		<div id="menu">
			<div id="accordion">
			  <div class="card">
				<div class="card-header" id="headingOne">
				  <h5 class="mb-0">
					<button class="btn btn-link" data-toggle="collapse" data-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
						<h1>About me</h1>
					</button>
				  </h5>
				</div>

				<div id="collapseOne" class="collapse" aria-labelledby="headingOne" data-parent="#accordion">
				  <div class="card-body">
					<div class="container">
						<div class="row">
							<div class="col-5">
								<p class="aboutTyping"></p>
								<div class="icons">
									<a href="mailto:tatianasofiagarrido@hotmail.com"><img src="icon/mail.png"></a>
									<a href="tel:+351910072665"><img src="icon/phone.png" id="pop" title="91 007 2665" data-placement="bottom"></a>
									<a href="https://www.linkedin.com/in/tatiana-garrido-9605751b1/"><img src="icon/linkedin.png"></a>
								</div>
							</div>
							<div class="col-7">
								<p>Hello again!</p>
								<p>I'm Tatiana, I'm from Setúbal, Portugal, and I'm looking for my first job in this area! <br>To get at this point, back in 2014 I took a <b>Visual Arts and Technologies degree</b> at ESELx, where I learned a bit of everything! From sculpture to 3D digital animation.<br>As I couldn't a job in the area I worked at contact centers until last September where I took a <b>Web Design</b> course at LSD</p>
								<p><span>But what am I?</span></p>
								<p><span class="cdr">Part < Coder ></span><br>
									I'm focused on writing clean and efficient code!<br>I know my way aroung HTML, CSS, JavaScript, PHP and SQL. I can also work with some frameworks like Bootstrap and jQuery.</p>
								<p><span class="dsgr">Part Designer</span><br>
									<span class="tiny">(Yeah I know I shouldn't use 4 different fonts on the same page, but I was feeling wild!)</span><br>
									I absolutely hate feeling lost or trapped on a website, that's why I'm very meticulous when it comes to user experience! After that it's the fun part using Adobe Illustrator and Photoshop to give colors and personality to a website!</p>
							</div>
						</div>
					</div>
				  </div>
				</div>
			  </div>
			  
			  <div class="card">
				<div class="card-header" id="headingTwo">
				  <h5 class="mb-0">
					<button class="btn btn-link collapsed" data-toggle="collapse" data-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
						<h1>Projects</h1>
					</button>
				  </h5>
				</div>
				<div id="collapseTwo" class="collapse" aria-labelledby="headingTwo" data-parent="#accordion">
				  <div class="card-body">
					Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. 3 wolf moon officia aute, non cupidatat skateboard dolor brunch. Food truck quinoa nesciunt laborum eiusmod. Brunch 3 wolf moon tempor, sunt aliqua put a bird on it squid single-origin coffee nulla assumenda shoreditch et. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident. Ad vegan excepteur butcher vice lomo. Leggings occaecat craft beer farm-to-table, raw denim aesthetic synth nesciunt you probably haven't heard of them accusamus labore sustainable VHS.
				  </div>
				</div>
			  </div>
			</div>
		</div>
		<div id="footer">
			<h1>Web Designer & Developer</h1>
		</div>
	</div>


		<!-- Optional JavaScript -->
		<!-- jQuery first, then Popper.js, then Bootstrap JS -->
		<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
		<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
		<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>
		<script src="https://cdn.jsdelivr.net/npm/typeit@7.0.4/dist/typeit.min.js"></script>
		<script type="text/javascript">
		
		
			new TypeIt('.typing', {
				strings: ["Oh, hello there!", "I'm Tatiana, nice to meet you and welcome to my portfolio"],
				speed: 1, /* 50 e no delay 5000*/
				waitUntilVisible: true
			}).go();
			
			new TypeIt('.tinyTyping', {
				startDelay: 1,
				cursor: false,
				strings: ["(Click anywhere to continue)"],
				speed: 1,
				waitUntilVisible: true
			}).go();
			
			new TypeIt('.aboutTyping', {
				speed: 70,
				waitUntilVisible: true,
				loop: true
			})
			.type("I'm perfectiomist", {delay: 500})
			.move(-3)
			.delete(1)
			.type('n')
			.move('END', {delay: 1500})
			.delete(13)
			.type('sophisticated')
			.pause(1500)
			.delete(13)
			.type('teaminded')
			.move(-5)
			.type('-m')
			.move('END', {delay: 1500})
			.delete(11)
			.type('passionate')
			.pause(1500)
			.delete(15)
			.type("Let's talk!", {delay: 2500})
			.go();
			
			
				$('#pop').tooltip();
	
			  
			  
			/** Committed Determined Passionate Persistent Motivated  Cheerful**/
			
			$('#entrada').click(function() {
				console.log('olá');
				$('#entrada').addClass('animate__animated');
				$('#entrada').addClass('animate__backOutDown');
				$('#accordion').css('display', 'block');
			});
			

			
		</script>
	</body>
</html>
