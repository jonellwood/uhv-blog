<script>
	import Nav from '../lib/components/nav.svelte';
	import Beans from './i-love-beans.svelte';
</script>

<Nav />
<div class="main">
	<div class="card">
		<h1>There should be an about me. Maybe it looks like a card?</h1>
	</div>
	<Beans />
</div>
<hr />

<style>
	.main {
		display: grid;
		grid-template-columns: 1fr 5fr;
		margin-top: 15px;
	}
	.card {
		width: 15em;
		border: 2px black solid;
		padding: 20px;
	}
</style>
