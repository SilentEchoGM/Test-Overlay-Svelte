<script>
  export let boost;
  let src;
  $: boost = Math.round(boost / 10) * 10;
  $: src = `/chevron/chevron_${boost} boost.png`;

  $: console.log(src);
</script>

<img {src} width="69" height="69" alt="" />
