<script>
    let initialCount = $props()

    let doubled = $derived(initialCount * 2)
</script>

<button on:click={() => initialCount++ }>
    clicks: {initialCount}
</button>

<span>doubled is {doubled}</span>