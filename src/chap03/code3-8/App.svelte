<script>
    let count = 0; // 상태값

    const handleClick = () => count = count + 1;
</script>
<button on:click = {handleClick}>
    클릭수 {count}
</button>