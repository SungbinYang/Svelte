<script>
	let name = 'world';
	let isRed = false;
</script>

<h1>Hello {name}!</h1>
<div class="box" 
		 style="background-color: {isRed ? 'red' : 'orange'};" 
		 on:click={() => isRed = !isRed}
		 on:mouseenter={() => name = 'Enter!'}
		 on:mouseleave={() => name = 'Leave!'}
		 >
	
</div>

<style>
	.box {
		width: 300px;
		height: 150px;
		background-color: orange
	}
</style>