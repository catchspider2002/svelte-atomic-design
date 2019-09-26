<script>
  export let label, value;
  import Progress from "./Atoms/AtomProgress.svelte";
</script>

<div class="container mx-auto w-3/12 flex">
  <span class="text-xs text-left w-6/12 flex-1">{label}</span>
  <span class="text-xs text-right w-6/12 order-2">{value}%</span>
</div>
<Progress {value} className="w-3/12" />
