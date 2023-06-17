<script lang="ts">
	import { onMount } from "svelte";

	import Reveal from "reveal.js";
	import "reveal.js/dist/reveal.css";
	import "reveal.js/dist/theme/black.css";

	import Slides from "./Slides.svelte";

	onMount(() => {
		const deck = new Reveal({
			plugins: [],
			autoAnimateEasing: "ease",
			autoAnimateDuration: 1,
			hash: true
		});
		deck.initialize();
	});
</script>

<div class="reveal">
	<div class="slides">
		<Slides />
	</div>
</div>
