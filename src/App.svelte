<script>
	import { ThemeWrapper, ThemeToggle } from 'svelte-themer'
</script>
  
<ThemeWrapper>
	<main>
		<h1>svelte themer</h1>
		<ThemeToggle />
	</main>
</ThemeWrapper>

<style>
	:global(html) {
		background-color: var(--theme-colors-background, initial);
		color: var(--theme-colors-text, initial);
	}
</style>