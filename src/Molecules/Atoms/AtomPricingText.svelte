<script>
  export let valid, value;
</script>

<li class={valid !== 'yes' ? 'disabledPricingText' : 'enabledPricingText'}>
  {value}
</li>
