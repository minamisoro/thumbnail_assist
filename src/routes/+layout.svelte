<script lang="ts">
	import Sidebar from "./.components/sidebar.svelte";
    import Container from "./.components/container.svelte";
    import Function from "./.components/function.svelte";

    const funcs: { name: String, id: Number }[] = [
        { name: "Color Analyzer", id: 1 }
    ];
</script>
<style>

</style>

<Sidebar>
    {#each funcs as { name, id } }
    <Function {name} {id}/>
    {/each}
</Sidebar>
<Container>
    <slot/>
</Container>