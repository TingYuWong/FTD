<!DOCTYPE html>
<html>
<head>
	<title></title>
	<!--bootstrap css-->
	<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/css/bootstrap.min.css" integrity="sha384-9aIt2nRpC12Uk9gS9baDl411NQApFmC26EwAOH8WgZl5MYYxFfc+NcPb1dKGj7Sk" crossorigin="anonymous">
	<link rel="stylesheet" type="text/css" href="0716.css">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

	<section id="header">
		<div class="container-fluid text-center">
			<div class="display-5">THE GREAT</div>
			<div class="display-4" id="rgbTitle"></div>
			<div class="display-5">GUESSING GAME</div>
		</div>
	</section>

	<section id="controlBar">
		<div class="container-fluid text-center">
			<div class="row justify-content-center">
				<div class="col-6">
					<div class="row justify-content-around">
						<div class="col-md-12 col-lg-4" id="reset">NEW COLORS</div>
						<div class="col-md-12 col-lg-4" id="hintMes"></div>
						<div class="col-md-12 col-lg-2" id="easy">EASY</div>
						<div class="col-md-12 col-lg-2" id="hard">HARD</div>
					
					</div>
				</div>
			</div>
		</div>
	</section>

	<section id="colorPalette">
		<div class="container-fluid">
			<!--row one-->
			<div class="row justify-content-center">
				<div class="col-6">
					<div class="row justify-content-between">
						<div class="col-sm-12 col-md-3 col-lg-3 colorBlock" id="0"></div>
						<div class="col-sm-12 col-md-3 col-lg-3  colorBlock" id="1"></div>
						<div class="col-sm-12 col-md-3 col-lg-3  colorBlock" id="2"></div>
					</div>
				</div>
			</div>

			<!--row two-->
			<div class="row justify-content-center rowTwo">
				<div class="col-6">
					<div class="row justify-content-between">
						<div class="col-sm-12 col-md-3 col-lg-3  colorBlock" id="3"></div>
						<div class="col-sm-12 col-md-3 col-lg-3  colorBlock" id="4"></div>
						<div class="col-sm-12 col-md-3 col-lg-3  colorBlock" id="5"></div>
					</div>
				</div>
			</div>
		</div>
	</section>




<!--bootstrap js-->
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.0/js/bootstrap.min.js" integrity="sha384-OgVRvuATP1z7JjHLkuOU7Xw704+h835Lr+6QL9UvYjZE3Ipu6Tp75j7Bh/kR0JKI" crossorigin="anonymous"></script>

<script type="text/javascript" src="0716.js"></script>


</body>
</html>
