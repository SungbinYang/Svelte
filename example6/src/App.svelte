<script>
	import Fruit from './Fruit.svelte';
	let fruits = [
		{name: 'Apple', color: 'red'},
		{name: 'banana', color: 'yellow'},
		{name: 'cherry', color: 'blue'},
	  {name: 'Orange', color: 'orange'}
	]
</script>

<ul>
	{#each fruits as {name, color} (name)}
		<Fruit fruit = {name} {color}/>
	{/each}
</ul>