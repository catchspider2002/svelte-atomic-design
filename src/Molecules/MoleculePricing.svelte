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

<div class="w-3/12 mx-auto text-center">
  <div
    class="pricingHeader bg-orange-400 relative flex items-center w-full p-2">
    <span class="text-white w-full">$50 /mo</span>
  </div>
  <div class="pricingBody">
    <h2 class="mt-4 font-bold text-xl mb-2">$50 /mo</h2>
    <ul class="list-none">
      {#each pricingData as { value, valid }, i}
        <PricingText {value} {valid} />
      {/each}
    </ul>
    <Button
      text="SMALL"
      className="text-white bg-orange-400 hover:bg-orange-700" />
    <Button
      text="MEDIUM"
      className="border-orange-500 text-orange-500 border-2
      hover:border-orange-300 hover:text-orange-300" />
    <Button text="LARGE" size="large" type="flat" />
  </div>
</div>
