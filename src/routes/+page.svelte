<script>
	import shabas from '../data/index';

	import sahabas from '../data/index';
	import Card from '../lib/components/Card.svelte';
</script>

<h1 class="title">The TEN to whom Paradise (Jannah) was promised.</h1>

<section class="items">
	{#each sahabas as sahaba}
		<Card>
			<span class="float-idx">{sahaba.id}</span>
			<a href={sahaba.link} target="_blank">{sahaba.name}</a>
		</Card>
	{/each}
</section>
