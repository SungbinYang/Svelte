<script>
	import Parent from './Parent.svelte'
	import {name} from './store.js'
</script>

<h1>Hello {$name}!</h1>
<Parent />