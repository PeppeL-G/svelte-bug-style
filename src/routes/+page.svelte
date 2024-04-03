<script>
	
	let numbers = [0, 1, 2]
	
</script>

<ul>
	{#each numbers as number}
		<li style:--number={number}>{number}</li>
	{/each}
</ul>