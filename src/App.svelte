<script>
	export let name;
	import FaSoundcloud from 'svelte-icons/fa/FaSoundcloud.svelte'
	import FaGithubAlt from 'svelte-icons/fa/FaGithubAlt.svelte'
	import FaInstagram from 'svelte-icons/fa/FaInstagram.svelte'
	import FaTwitch from 'svelte-icons/fa/FaTwitch.svelte'
	import FaTwitter from 'svelte-icons/fa/FaTwitter.svelte'
	import FaYoutube from 'svelte-icons/fa/FaYoutube.svelte'
</script>
<main>
	<h1 class='title'>Gravitinos</h1>
	<p>Web Developer for money 🕸</p>
	<p>Everything else for fun</p>
	<div class='links'>
		<a class='link' href="https://github.com/xvalentino"><div class='icon'><FaGithubAlt /></div>Github</a>
		<a class='link' href="https://soundcloud.com/gravitinos-98277575"><div class='icon'><FaSoundcloud /></div>Soundcloud</a>
		<a class='link' href="https://instagram.com/gravitinos"><div class='icon'><FaInstagram /></div>Instagram</a>
	    <a class='link' href="https://twitch.tv/gravitinos"><div class='icon'><FaTwitch /></div>Twitch</a>
	    <a class='link' href="https://twitter.com/gravitinos"><div class='icon'><FaTwitter /></div>Twitter</a>
		<a class='link' href="https://www.youtube.com/channel/UCampr6MQmkwZPLI2-fzKRXQ"><div class='icon'><FaYoutube /></div>Youtube</a>
	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.icon {
		width: 32px;
		height: 32px;
	}

	.links {
		align-items: center;
		justify-content: space-evenly;
		display: flex;
		flex-direction: column;
	}

	.link {
		align-items: center;
		display:flex;
		flex-direction:column;
		justify-content: center;
		padding: 1rem;
	}

	.title {
		color: white;
		text-transform: lowercase;
		font-size: 4em;
		font-weight: 150;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}


</style>