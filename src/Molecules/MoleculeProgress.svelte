<script>
  export let label, value;
  import Progress from "./Atoms/AtomProgress.svelte";
</script>

<div className="grid-2 moleculeProgress">
  <span className="smallest-text text-left grid-item-1">{label}</span>
  <span className="smallest-text text-right grid-item-2">{value}%</span>
  <Progress {value} />
</div>
