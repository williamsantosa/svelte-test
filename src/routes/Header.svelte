<script lang="ts">
	let { 
        name
     }: { 
        name: string
     } = $props();
</script>

<div>
    {#if name}
        <h1>{name}'s Form</h1>
    {/if}
</div>

<style>
    div {
        background: red;
    }
</style>