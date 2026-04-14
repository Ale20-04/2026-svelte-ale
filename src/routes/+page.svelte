<script>
    let count = $state(0)
    let multiplier = $state(2)
    let doubled = $derived(count * 2)
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<button on:click={() => count++ }>
    clicks: {count}
</button>

<button on:click={() => multiplier++ }>
    multiplier: {multiplier}
</button>
<span>doubled is {doubled}</span>
<style>
    h1 {
        color: aqua;
    }

</style>

