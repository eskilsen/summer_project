<script>
    import {Footer, Button, MaterialApp} from 'svelte-materialify';

    const links = ["Home", "About", "Team", "Services", "Contact Us"];

</script>
<div class="footer">
<MaterialApp>
    <Footer padless class = "indigo theme--dark justify-center flex-column">
        <div class="mt-2 mb-2">
            {#each links as link}
            <Button text rounded>{link}</Button>
            {/each}
        </div>
        <div class= "indigo lighten-1 pa-2 text-center" style="width:100%">
            2020 - <b>Svenny & Essi</b>
        </div>
    </Footer>
</MaterialApp>
</div>

<style>
    .footer{
        position: absolute;
        bottom: 0;
        width: 100%;
    }
</style>