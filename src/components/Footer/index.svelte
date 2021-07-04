<script context="module">
	export const prerender = true;
</script>

<footer>
	<div class="f1">
		<h3>Address</h3>
		<p>Kinyamo Inc.</p>
		<p>Mambo Leo building</p>
		<p>Bogi Benda Street, off North Road A.</p>
		<p>+254700 000 000</p>
	</div>
	<div class="f2">
		<h3>Quick Links</h3>
		<ul class="pages">
			<li><a href="/concept">Concept</a></li>
			<li><a href="/implementation">Implementation</a></li>
			<li><a href="/contribution">Contribution</a></li>
		</ul>
	</div>
	<div />
</footer>

<style>
	footer {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
		position: sticky;
		bottom: 0;
		width: inherit;
		padding: 10px;
		background-color: rgba(64, 224, 208, 0.144);
	}
	.f1,
	.f2 {
		display: flex;
		flex-direction: column;
	}
	ul {
		list-style: none;
		display: flex;
		flex-direction: column;
	}
	li {
		padding: 5px;
	}
</style>
