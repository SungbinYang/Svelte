<script>
	let name = 'world';
	let isActive = false;
	
	function abc() {
		name = 'ROVERT';
		isActive = true;
	}
</script>

<h1 class:active={isActive}>Hello {name}!</h1>
<input type="text" bind:value={name} />
<button on:click={abc}>
	Click
</button>

<style>
	h1.active {
		color: slateBlue;
	}
</style>