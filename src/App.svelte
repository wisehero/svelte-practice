<script>
    import Middle from './chap03/code3-32_3-34/middle.svelte';

    let count = 0;

    const handleClick = () => count = count + 1;
</script>
<Middle {count} {handleClick}></Middle>