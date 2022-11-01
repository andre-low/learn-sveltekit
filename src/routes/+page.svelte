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
	<section class="grid h-1/2 lg:h-full place-content-center bg-sky-500 text-center">
		<h1 class="text-slate-50 text-[5rem] font-bold z-20">Twittr 🐦️</h1>
		<p class="text-slate-50 text-2xl font-bold bg-slate-900 rotate-2 -translate-y-8 z-10 p-3.5">Share your hot take with everyone.</p>
	</section>

	<section class="grid h-1/2 lg:h-full place-content-center">
		<a class="text-slate-50 text-lg font-bold rounded-3xl bg-sky-500 py-3.5 px-8" href="/home">🔥 Share your hot take</a>
	</section>
</main>
