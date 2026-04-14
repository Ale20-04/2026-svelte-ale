<script>
    let { initialCount: count = $bindable()} = $props()

    let doubled = $derived(count * 2)
</script>

<button on:click={() => count++ }>
    clicks: {count}
</button>

<span>doubled is {doubled}</span>