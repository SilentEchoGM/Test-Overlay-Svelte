<script>
  import Chevron from "./Chevron.svelte";

  let boost = 100;
  $: boost = boost;
</script>

<input type="number" bind:value={boost} />

<Chevron {boost} />
