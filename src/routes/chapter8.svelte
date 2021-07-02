
<title>Chapter 8</title>
<main>
	<div class="chapter chapter 2">
		<div class="head">
			<div class="tit">Chapter 8</div>

	
		<button class="pushable">
			<a href="/">
		  <span class="btn">
		    <i class="far fa-caret-left"></i>
		  </span>
		  </a>
		</button>
			
		</div>


		<div class="inf">Credentials</div>
		<div class="form">
			<input type="text" placeholder="Enter your first name">
			<input type="text" placeholder="Enter your last name">
			<input type="number" placeholder="Enter your age" >
			<input type="email" placeholder="Enter your email">
			<input class="sub" type="submit" value="Send">
		</div>
	</div>
</main>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

	main {
		font-family: 'Montserrat', sans-serif;
		height: 100%;
		min-height: 98vh;
		background: #43294a;
	}

	.chapter {
		width: 500px;
		margin: 0 auto;
		padding-top: 80px;
		color: white;
	}

	.inf {
		font-size: 20px;
		font-weight: 800;
		margin-bottom: 15px;
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

	.form {
		width: 100%;
	}

	input {
		width: 100%;
		padding: 20px 15px;
		border: 0;
		outline: 0;
		margin-bottom: 15px;
		box-sizing: border-box;
		border-radius: 8px;
		background: #1f2937;
		color: white;
		font-family: 'Montserrat', sans-serif;
	}

	input::placeholder {
		color: white;
	}

	.sub {
		background: #FF6B81;
		color: white;
	}

	.sub:hover {
		background: #FFB6B3;
		cursor: pointer;
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
