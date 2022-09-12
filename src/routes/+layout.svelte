<script>
	import '../styles/sweet.css';
	import '../styles/fonts.css';
	import '../styles/global.css';
  import AppHeader from '../lib/AppHeader.svelte';
</script>

<main>
  <AppHeader />
  <slot />
</main>