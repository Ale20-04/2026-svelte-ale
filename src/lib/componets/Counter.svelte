<script>
    let props = $props()

    let count = $state(props.initialCount)
    let doubled = $derived(count * 2)
</script>

<button on:click={() => count++ }>
    clicks: {count}
</button>

<span>doubled is {doubled}</span>