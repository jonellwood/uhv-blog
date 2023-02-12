<script>
	import Logo from './logo.svelte';
</script>

<div class="nav">
	<p>Blog</p>
	<p>Weight</p>
	<Logo />
	<p>Activity</p>
	<p>Eating</p>
</div>

<style>
	@font-face {
		font-family: Rubik;
		src: url('../../../static/fonts/Rubik/Rubik-VariableFont_wght.ttf');
	}
	.nav {
		font-family: Rubik;
		width: 100vw;
		margin-top: 0;
		margin-left: 0;
		margin-right: 0;
		padding-left: 1px;
		padding-right: 1px;
		display: grid;
		grid-template-columns: 1fr 1fr 5fr 1fr 1fr;
		background-color: #1c1626;
		color: bisque;
		justify-content: center;
		justify-items: center;
	}
	.nav p {
		align-self: center;
		font-size: 1.5em;
	}
</style>
