<script>
    import Character from "./Character.svelte"

    export let chars
</script>

<div>
    {#each chars as char}
        <Character {char} />
    {/each}
</div>