<script>
	// your script goes here
</script>

<header>
	<div class="corner">
		<a href="/">KINYAMO</a>
	</div>
	<ul class="pages">
		<li><a href="/concept">Concept</a></li>
		<li><a href="/implementation">Implementation</a></li>
		<li><a href="/contribution">Contribution</a></li>
	</ul>
</header>

<style>
	header {
		position: fixed;
		top: 0;
		width: 100vw;
		height: 55px;
		margin: 0;
		padding: 10px;
		box-sizing: border-box;
		box-shadow: 0px 8px 10px #00000020;
		display: flex;
		align-items: center;
		justify-content: space-between;
	}
	.corner {
		font-size: 20px;
		font-weight: 800;
		color: black;
	}
	.corner a:hover {
		background-color: transparent;
		color: #0d0;
		text-decoration: none;
	}
	ul {
		list-style: none;
		display: flex;
		flex-direction: row;
	}
	li {
		padding: 5px;
	}
</style>
