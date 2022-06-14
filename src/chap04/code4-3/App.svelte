<script>
    let x = 11;
</script>
{#if x > 10}
    <p>{x}는 10보다 크다</p>
{:else if 5 > x}
    <p>{x}는 5보다 작다.</p>
{:else}
    <p>{x}는 5와 10 사이다.</p>
{/if}
