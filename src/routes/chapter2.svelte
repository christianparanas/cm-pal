
<title>Exercise_#2</title>
<main>
	<div class="chapter chapter 2">
		<div class="head">
			<div class="tit">Chapter 2</div>

			<a href="/">
				<button class="pushable">
				  <span class="btn">
				    <i class="far fa-caret-left"></i>
				  </span>
				</button>
			</a>
		</div>


		<p><b>WELCOME TO HTML</b></p>
		<p><b>Eastern Visayas State University</b></p>
		<p><i>College of Engineering</i></p>
		<p><b><i>Information Technology Department</i></b></p>
	</div>
</main>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

	main {
		font-family: 'Montserrat', sans-serif;
		height: 98vh;
		background: #43294a;
	}

	.chapter {
		width: 500px;
		margin: 0 auto;
		padding-top: 80px;
		color: white;
	}

	.head {
		display: flex;
		justify-content: space-between;
	}

	.tit {
		font-size: 20px;
		font-weight: 700;
		width: fit-content;
		margin: 0 0 60px;
		background: #052939;
		padding: 15px 25px;
	}

	.pushable {
		height: fit-content;
		-webkit-tap-highlight-color: transparent;
    background: #091a28;
    border-radius: 50%;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
    outline: none;
  }

	.btn {
    display: block;
    padding: 15px 25px;
    border-radius: 50%;
    font-family: 'Montserrat', sans-serif;
    font-size: 1.25rem;
    font-weight: 700;
    background: #1f2937;
    color: white;
    transform: translateY(-6px);
  }

  .pushable:active .btn {
    transform: translateY(-2px);
  }

  .pushable:hover .btn {
  	background: #fcedd8;
  	color: #052939;
  }

	p {
		margin-top: 0;
	}

	@media only screen and (max-width: 700px) {
		.chapter {
			width: 90%;
			margin: 0 auto;
			padding-top: 50px;
			color: white;
		}
	}
	
</style>
