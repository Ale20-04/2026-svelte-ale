<script>
    let count = $state(0);
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://svelte.dev/docs/kit">svelte.dev/docs/kit</a> to read the documentation</p>

<button on:click={() => count++ }>
    clicks: {count}
</button>

<style>
    h1 {
        color: aqua;
    }

</style>

