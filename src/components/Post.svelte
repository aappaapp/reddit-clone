<script lang="ts">
    export let path: string;

    function onClick() {
        location.href = path;
    }
</script>

<button on:click={onClick}>{path}</button>
