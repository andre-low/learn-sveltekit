<script lang="ts">
	import { fly } from 'svelte/transition'
</script>

<svelte:head>
	<title>Twittr</title>
</svelte:head>

<main
	class="h-screen lg:grid lg:grid-cols-2 bg-slate-900"
	in:fly={{ x: -100, duration: 250, delay: 300 }}
	out:fly={{ x: -100, duration: 250 }}
>
	<section class="grid h-1/2 lg:h-full place-content-center bg-sky-500">
		<h1 class="text-slate-50">Twittr 🐦️</h1>
		<p class="text-slate-50">Share your hot take with everyone.</p>
	</section>

	<section class="grid h-1/2 lg:h-full place-content-center">
		<a class="text-slate-50" href="/home">🔥 Share Your Hot Take</a>
	</section>
</main>
