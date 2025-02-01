<script>
    import Psidebar from "../../lib/Psidebar.svelte";
</script>

<div>
    <Psidebar />
    <main>
        <slot />
    </main>
</div>

<style>
    div {
        display: flex;
        padding-top: 5px;
        padding-bottom: 5px;
    }
</style>