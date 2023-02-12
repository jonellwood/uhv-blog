<script>
	import { opacity } from '../lib/components/store.js';

	let thisOpacity;
	opacity.subscribe((value) => {
		thisOpacity = value;
	});
</script>

<div class="container-for-everything">
	<article>
		<h1>🤟 I love beans 🫘</h1>
		<p>Beans Beans the 🎵 musical fruit 🥝</p>
		<p>The more you eat, the more you toot</p>
	</article>
</div>

<style>
	.container-for-everything {
		background: rgba(37, 70, 125, var(--opacity));
		font-size: var(--font-size);
	}
</style>
