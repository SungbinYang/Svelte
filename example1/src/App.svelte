<script>
	const a = 'ABC'
	let name = 'world';
	let age = 85;
	
	function abc() {
		name = 'ROVERT';
	}
</script>

<h1>Hello {name}!</h1>
<h2>
	{a}
</h2>
<button on:click={abc}>
	Click
</button>

<style>
	h1 {
		color: red;
	}
</style>