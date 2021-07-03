<script>
	let fruits = ['Apple', 'Banana', 'Cherry', 'Orange', 'Mango'];
	
	function deleteFruit() {
		fruits.splice(2, 1)
		fruits = fruits
	}
</script>

<button on:click={deleteFruit}>
	Click!
</button>
<ul>
	{#each fruits as fruit (fruit)}
			<li>{fruit}</li>
	{/each}
</ul>