<script>
    import Child from './chap03/code3-25_3-26/child.svelte';

    let count = 0;

    const handleClick = () => count = count + 1;
</script>
<Child carryValue={count}/>
<button on:click={handleClick}>클릭</button>