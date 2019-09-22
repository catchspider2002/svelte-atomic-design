<script>
  export let value;

  let valuePercent = "width:" + { value } + "%";
</script>

<style>
  .progress {
    height: 0.4rem;
    grid-column-start: 1;
    grid-column-end: span 2;
  }
</style>

<div class="progress">
  <div
    style="width:{value}%"
    class="progress-bar"
    role="progressbar"
    aria-valuenow={value}
    aria-valuemin="0"
    aria-valuemax="100" />
</div>
