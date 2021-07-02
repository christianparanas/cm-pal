

<title>Chapter 5</title>
<main>
	<div class="chapter chapter 2">
		<div class="head">
			<div class="tit">Chapter 5</div>

	
		<button class="pushable">
			<a href="/">
		  <span class="btn">
		    <i class="far fa-caret-left"></i>
		  </span>
		  </a>
		</button>
			
		</div>


		<p><b>Unordered List</b></p>
		<ul type="square">
			<li>List Item 1</li>
			<li>List Item 2</li>
			<li>List Item 3</li>
			<li>List Item 4</li>
			<li>List Item 5</li>
		</ul>
		
		<p><b>Ordered List</b></p>
		<ol>
			<li>List Item 1</li>
			<li>List Item 2</li>
			<li>List Item 3</li>
			<li>List Item 4</li>
			<li>List Item 5</li>
		</ol>
		
		<p><b>Unordered List in a Ordered List</b></p>
		<ol type="A">
			<li>List Item 1</li>
			<li>List Item 2</li>
			<li>List Item 3</li>
			<li>List Item 4</li>
			<li>List Item 5</li>
				<ul type="square">
				<li>List Item 1</li>
				<li>List Item 2</li>
				<li>List Item 3</li>
				<li>List Item 4</li>
				<li>List Item 5</li>
				</ul>
		</ol>
		
		<p><b>Ordered List in a Unordered List</b></p>
		<ul>
			<li>List Item 1</li>
			<li>List Item 2</li>
			<li>List Item 3</li>
			<li>List Item 4</li>
			<li>List Item 5</li>
				<ol type="a" start="1">
				<li>List Item 1</li>
				<li>List Item 2</li>
				<li>List Item 3</li>
				<li>List Item 4</li>
				<li>List Item 5</li>
				</ol>
		</ul>
		
		<p><b>Description List</b></p>
		<dl>
			<dt>Term 1</dt>
				<dd>This is the description of the term.</dd>
		</dl>
		<dl>
			<dt>Term 2</dt>
				<dd>This is the description of the term.</dd>
		</dl>
		<dl>
			<dt>Term 3</dt>
				<dd>This is the description of the term.</dd>
		</dl>
	</div>
</main>


<style>
	@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');

	main {
		font-family: 'Montserrat', sans-serif;
		height: 100%;
		background: #43294a;
	}

	.chapter {
		width: 500px;
		margin: 0 auto;
		padding-top: 80px;
		color: white;
		padding-bottom: 100px;
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
