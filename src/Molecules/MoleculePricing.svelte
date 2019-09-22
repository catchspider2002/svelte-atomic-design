<script>
  import PricingText from "./Atoms/AtomPricingText.svelte";
</script>

<div class="pricingTable col-4">
  <div class="pricingHeader">
    <span>$50 /mo</span>
  </div>
  <div class="pricingBody">
    <h2 class="text-center">$50 /mo</h2>
    <ul class="list-unstyled">
      <PricingText value="Lorem Ipsum Service 5" valid="yes" />
      <PricingText value="Lorem Ipsum Service 2" valid="yes" />
      <PricingText value="Lorem Ipsum Service 3" valid="no" />
      <PricingText value="Lorem Ipsum Service 4" valid="yes" />
      <PricingText value="Lorem Ipsum Service 5" valid="no" />
      <PricingText value="Lorem Ipsum Service 6" valid="no" />
    </ul>
  </div>
</div>
