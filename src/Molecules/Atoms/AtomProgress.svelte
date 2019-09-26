<script>
  export let value, className;
</script>
<div class="bg-red-200 rounded flex h-2 overflow-hidden text-xs mx-auto {className}">
  <div
    style="width:{value}%"
    class="bg-red-500"
    role="progressbar"
    aria-valuenow={value}
    aria-valuemin="0"
    aria-valuemax="100" />
</div>
