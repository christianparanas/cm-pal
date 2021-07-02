
<script>
	export const chaps = [['Chapter 2', 'chapter2'], ['Chapter 3', 'chapter3'], ['Chapter 4', 'chapter4'], ['Chapter 5', 'chapter5'], ['Chapter 6', 'chapter6'], ['Chapter 7', 'chapter7'], ['Chapter 8', 'chapter8'], ['Chapter 9', 'chapter9']];
</script>

<main>
	<div class="text">Juvie Ann Palaña</div>

	<div class="links">
		{#each chaps as chap}
			<a href={`/${chap[1]}`}>
				<button class="pushable">
				  <span class="btn">
				    {chap[0]}
				  </span>
				</button>
			</a>
		{/each}
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

	main {
		height: 98vh;
		background: #43294a;
	}

	.text {
		margin: 0 20px;
		font-size: 5rem;
	  text-align: center;
	  padding-top: 150px;
    color: #fcedd8;
   	font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    text-shadow: 5px 5px 0px #eb452b, 
                10px 10px 0px #efa032, 
                15px 15px 0px #46b59b, 
                20px 20px 0px #017e7f, 
                25px 25px 0px #052939;
	}

	.links {
		display: grid;
		grid-template-columns: repeat(8, 1fr);
		grid-gap: 15px;
		width: fit-content;
		margin: 100px auto 0;
	}

	 .pushable {
		-webkit-tap-highlight-color: transparent;
    background: #091a28;
    border-radius: 12px;
    border: none;
    padding: 0;
    cursor: pointer;
    outline-offset: 4px;
    outline: none;
  }

	.btn {
    display: block;
    padding: 15px 25px;
    border-radius: 12px;
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

  @media only screen and (max-width: 700px) {
  	.text {
		  font-size: 50px;
		  text-align: center;
		  padding-top: 90px;
	    color: #fcedd8;
	    font-weight: 700;
	    text-shadow: 2px 2px 0px #eb452b, 
	                4px 4px 0px #efa032, 
	                7px 7px 0px #46b59b, 
	                8px 8px 0px #017e7f, 
	                10px 10px 0px #052939;
		}


  	.links {
			display: grid;
			grid-template-columns: repeat(2, 1fr);
			grid-gap: 15px;
			width: fit-content;
			margin: 100px auto 0;
		}

		.btn {
	    display: block;
	    padding: 13px 20px;
	    border-radius: 12px;
	    font-size: 1.25rem;
	    font-weight: 700;
	    background: #1f2937;
	    color: white;
	    transform: translateY(-6px);
  	}
  }

</style>