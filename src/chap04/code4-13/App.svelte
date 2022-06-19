<script>
    let numbers = [
        'one',
        'two',
        'three'
    ]

    let getNumbers = []
</script>
{#each numbers as number}
    <label>
        <input type="checkbox" bind:group={getNumbers} value={number}>
    </label>
{/each}
{getNumbers}