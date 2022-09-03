<script>
	import sahabas from '../data/index';
</script>

<h1>The TEN to whom Paradise (Jannah) was promised.</h1>

<ul>
	{#each sahabas as sahaba}
		<li>
			<div class="card">
				<a href={sahaba.link} target="_blank">{sahaba.name}</a>
			</div>
		</li>
	{/each}
</ul>
