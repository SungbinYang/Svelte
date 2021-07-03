<script>
	let name = 'world';
	let isShow = false;
	
	function toggle() {
		isShow = !isShow
	}
</script>

<button on:click={toggle}>
	Click!
</button>
{#if isShow}
	<h1>Hello {name}!</h1>
{:else if name === 'world'}
	<h3>
		Svelte	
	</h3>
{:else}
	<h2>
		Sungbin!	
	</h2>
{/if}