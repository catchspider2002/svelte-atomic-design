<script>
  export let valid, value;
</script>

<li class={valid === 'no' ? 'line-through' : ''}>{value}</li>
