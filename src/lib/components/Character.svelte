<script lang="ts">
	const UNKNOWN_IMAGE_URL = 'https://bobsburgers-api.herokuapp.com/images/characters';
	export let name = '';
	export let image = UNKNOWN_IMAGE_URL;
	export let gender = '';
	export let hairColor = '';
	export let occupation = '';
	export let firstEpisode = '';
	export let voicedBy = '';
</script>

<article>
	<header><i>Bob's Burgers</i> character</header>
	<figure class="image">
		<img alt={name} src={image} loading="lazy" />
	</figure>
	<section>
		<h1>Name</h1>
		<dl>
			<dt>Gender</dt>
			<dd>{gender ?? ''}</dd>
		</dl>
	</section>
</article>
