# solar-systm.io
this is a solar-system using html &amp; css 
<!DOCTYPE html>
	<head>
		<title>Solar System</title>
		<meta charset="utf-8" name="viewpoint" content="width=device-width,initial-scale=1.0">
		<meta name="description" content="The Solar System">
		<meta name="robots" content="index,follow">
		<style type="text/css">
			.container{
				width: 500px;
				height: 400px;
				margin: 80px auto;
				background: linear-gradient(-45deg,#020024, #702e8c,#9d92e8);
				position: relative;
				background-size: 400% 400%: 
			}
			.contain{
				position: absolute;
				top: 50%;
				left: 50%;
				transform: translate(-50%,-50%);
			}
			.solar-system{
				width: 15rem;height: 15rem;
			}
			.planet {
				display: flex;
				align-items: center;
				justify-content: center;
				border-radius: 50%;
				border: 3px solid #dedede;
				animation-name: rotatePlanet;
				animation-timing-function: linear;
				animation-iteration-count: infinite;
				animation-duration: 15s; 
			}
			.planet:after {
				content: '';
				border-radius: 50%;
				position: absolute;
			}
			.planet1 {
				width: 100%;height: 100%;
				animation-duration: 25s;
			}
			.planet1:after {
				width: 1.8rem;height: 1.8rem;
				top: -15px;background: #8a8380;
			}
			.planet2 {
				width: 75%;height: 75%;
				animation-duration: 18s;
			}
			.planet2:after {
				width: 1.3rem;height: 1.3rem;
				top: -10px;background: #ab711d;
			}
			.planet3 {
				width:77%;height: 77%;
				animation-duration: 13s;
			}
			.planet3:after {
				width: 0.9rem;height: 0.9rem;
				top: -8px;background: #ffddab;
			}
			.planet4 {
				width: 55%;height: 55%;
				animation-duration: 9s;
			}
			
			.planet4:after {
				width: 0.6rem;height: 0.6rem;
				top: -6px;background: #82c8ff;
			}
			.sun {
				width: 45%;height: 44.5%;
				background: #ffc107;border-radius: 50%;
			}
			@keyframes rotatePlanet{
				from{ transform: rotate(0);  }
				to { transform: rotate(360deg); }
			}
		</style>
	</head>
	<body>
	<div class="container">	
	  <div class="contain">	
		<div class="solar-system" >
			<div class="planet planet1">
				<div class="planet planet2">
					<div class="planet planet3">
						<div class="planet planet4">
						<div class="sun">
							
						</div>	
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	</div>	
	</body>
</html>
