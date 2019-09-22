<script>
  export let value;
</script>

<div class="progress">
  <div
    style="width:{value}%"
    class="progress-bar"
    role="progressbar"
    aria-valuenow={value}
    aria-valuemin="0"
    aria-valuemax="100" />
</div>
