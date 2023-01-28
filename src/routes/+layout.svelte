<script lang="ts">
	import { Navbar } from '$lib/components';
</script>

<div class="app">
	<Navbar />
	<div class="content">
		<slot />
	</div>
</div>

<style>
	@font-face {
		font-family: 'SourceCodePro';
		src: url('/fonts/SourceCodePro-Regular.ttf') format('ttf');
		font-weight: normal;
		font-style: normal;
		font-display: swap;
	}

	@font-face {
		font-family: 'SourceCodePro';
		src: url('/fonts/SourceCodePro-Bold.ttf') format('ttf');
		font-weight: bold;
		font-style: bold;
		font-display: swap;
	}

	.app {
		font-family: 'SourceCodePro', monospace;
		margin: 1rem;
	}

	.content {
		margin: 2rem 0rem;
		height: 100%;
	}

	.footer {
		padding: 1rem;
		height: 20px;
	}

	:global(a) {
		color: #e02828;
		text-decoration: none;
	}

	:global(a:hover) {
		text-decoration: underline;
	}

	:global(li) {
		font-weight: 700;
		margin: 0.5rem 0;
	}
</style>
