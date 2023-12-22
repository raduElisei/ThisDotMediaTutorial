<script lang="ts">
	let subject = 'Learners';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<h1>Welcome {subject}!</h1>

<a href="/about">About</a>
<a href="/characters">Characters</a>

<style>
	h1 {
		color: rebeccapurple;
	}
</style>
