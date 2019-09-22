<script>
  let name = "world!";
  import Card from "./Molecules/MoleculeCard.svelte";
  import Progress from "./Molecules/MoleculeProgress.svelte";
  import Pricing from "./Molecules/MoleculePricing.svelte";
</script> 

<h1>Hello {name}!</h1>
<span className="title">React App</span>
<Progress label="WordPress" value="90" />
<Progress label="CSS" value="40" />
<p />
<Pricing title="" val1="" val2="" val3="" val4="" val5="" val6="" />
<Card title="New title" subtitle="Sub" />
 