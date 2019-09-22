<script>
  import PricingText from "./Atoms/AtomPricingText.svelte";
  import Button from "./Atoms/AtomButton.svelte";
  let pricingData = [
    { value: "Lorem Ipsum Service 1", valid: "yes" },
    { value: "Lorem Ipsum Service 2", valid: "yes" },
    { value: "Lorem Ipsum Service 3", valid: "no" },
    { value: "Lorem Ipsum Service 4", valid: "yes" },
    { value: "Lorem Ipsum Service 5", valid: "yes" },
    { value: "Lorem Ipsum Service 6", valid: "no" }
  ];
</script>

<div class="pricingTable col-4">
  <div class="pricingHeader">
    <span>$50 /mo</span>
  </div>
  <div class="pricingBody">
    <h2 class="text-center">$50 /mo</h2>
    <ul class="list-unstyled">
      {#each pricingData as { value, valid }, i}
        <PricingText {value} {valid} />
      {/each}
      <!-- <PricingText value="Lorem Ipsum Service 5" valid="yes" />
      <PricingText value="Lorem Ipsum Service 2" valid="yes" />
      <PricingText value="Lorem Ipsum Service 3" valid="no" />
      <PricingText value="Lorem Ipsum Service 4" valid="yes" />
      <PricingText value="Lorem Ipsum Service 5" valid="no" />
      <PricingText value="Lorem Ipsum Service 6" valid="no" /> -->
    </ul>
    <Button text="BUY NOW" />
  </div>
</div>
