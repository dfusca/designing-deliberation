<script>
	import HeaderBar from '$lib/HeaderBar.svelte';
	import { base } from '$app/paths';
    import { setBeginner } from '$lib/userMode.svelte.js';
</script>

<svelte:head>

<title>Designing Deliberation</title>

</svelte:head>

<HeaderBar/>
<div class="page">
	<h3>How do you design engagement for decisions that stick? </h3>
	<p>
		A tool for anyone designing a process that includes the public, from engagement practitioners to policy and planning teams. 
	</p>

	<ol>
		<li><strong>Find your level.</strong> How much should the public shape this decision? </li>
		<li><strong>Decide how deep to go.</strong> Does this decision need the public to work through hard trade-offs, or will a lighter process hold up? </li>
		<li><strong>Frame the process.</strong> Map the stages of your process and what each one should deliver.  </li>
		<li><strong>Design how people decide together.</strong> If the answer to step 2 is yes, plan how that happens. </li>
	</ol>

	<div class="choices-container">
		<a href="/designing-deliberation/case-studies" class="choice-box beginner"
			onclick={() => setBeginner(true)}>
			<h2> I am a beginner</h2>
			<p>Guide me through the process step-by-step!</p>
		</a>

		<a href="/designing-deliberation/interactive-tool" class="choice-box experienced"
			onclick={() => setBeginner(false)}>
			<h2> I have experience doing this! </h2>
			<p>Take me directly to the framework builder tool!</p>
		</a>
	</div>
</div>

<style>
	.page {
		max-width: 1500px;
		width: 95%;
		padding-left: calc((100dvw - min(95%, 1500px))/2);
		padding-top: 40px;
	}

	h1 {
		font-size: 50px;
	}

</style>

