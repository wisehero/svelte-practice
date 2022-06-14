<script>
    let user = {loggedIn: false}

    function toggle() {
        user.loggedIn = !user.loggedIn;
    }
</script>
{#if user.loggedIn}
    <button on:click={toggle}>
        Log out
    </button>
    <p>로그인 상태입니다.</p>
{:else}
    <button on:click={toggle}>
        Log in
    </button>
    <p>로그아웃 상태입니다.</p>
{/if}

<!--if 블럭을 두개로 만들지 않고 if-else로 처리-->