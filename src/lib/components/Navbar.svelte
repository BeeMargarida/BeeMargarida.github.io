<script lang="ts">
	import github from '$lib/assets/github.svg';
</script>

<div class="navbar">
	<div class="left">
		<a href="/">BeeMargarida</a>
	</div>
	<div class="right">
		<a href="/">home</a>
		<a href="/cv">actual CV</a>
		<!-- <a href="/fun-stuff">fun stuff</a>
		<a href="/brain-dump">brain dump</a> -->
		<a class="github" href="https://github.com/BeeMargarida" target="_blank" rel="noreferrer"
			><img alt="Github icon" src={github} /></a
		>
	</div>
</div>

<style>
	.navbar {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
	}

	.right {
		display: flex;
		flex-direction: row;
		justify-content: space-between;
		gap: 1rem;
	}

	.github img {
		width: 20px;
		height: 20px;
	}
</style>
