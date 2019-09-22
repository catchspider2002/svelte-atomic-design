<script>
  export let label, value;
  import Progress from "./Atoms/AtomProgress.svelte";
</script>

<div class="grid-2 moleculeProgress">
  <span class="smallest-text text-left grid-item-1">{label}</span>
  <span class="smallest-text text-right grid-item-2">{value}%</span>
  <Progress {value} />
</div>
