<script>
    const pages = ["Hello", "Ciao", "Nihao"]
</script>

<div class="header">
    {#each pages as page}
    <button>{page}</button>
    {/each}
</div>



<style>
    .header {
        position: absolute;
        top: 0;
        width: 100%;
        background-color: red;


    }
</style>