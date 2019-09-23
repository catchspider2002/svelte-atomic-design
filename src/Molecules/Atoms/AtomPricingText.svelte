<script>
  export let valid, value;
</script>

<li class={valid === 'yes' ? 'enabledPricingText' : 'disabledPricingText'}>
  {value}
</li>
