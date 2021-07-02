
<title>Chapter 3</title>
<main>
	<div class="chapter chapter 2">
		<div class="head">
			<div class="tit">Chapter 3</div>

	
		<button class="pushable">
			<a href="/">
		  <span class="btn">
		    <i class="far fa-caret-left"></i>
		  </span>
		  </a>
		</button>
			
		</div>


		<p>
			<b><u>Personal Information:</u><b>
<pre>
Last Name	:	Palana
First Name	:	Juvie Ann
Middle Name	:	Advento
Age		:	20
Birthday	:	July 20, 2000
</pre>

<b><u>Educational Attainment</u></b>
<pre>

Elementary      : 	MacArthur Central School
Year Graduated  :	2011-2012
	
Secondary	:	MacArthur National High Sschool
Year Graduated	:	2015-2016
	
Tertiary	:	Eastern Visayas State University
Degree		:	Bachelor of Science in Informatin Technology
Year Graduated  :	2021
</pre>
		</p>
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
		overflow-x: auto;
	}

	@media only screen and (max-width: 700px) {
		.chapter {
			width: 90%;
			margin: 0 auto;
			padding-top: 50px;
			color: white;
		}

			p {
		margin-top: 0;
	}
	}
	
</style>