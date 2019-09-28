<script>
  export let text, className;
  // import msg from "../../../../tailwind.config.js";

  // console.log(msg.theme.colors.gray);
</script>

<button type="button" class="font-bold py-2 px-4 rounded text-base {className}">
  {text}
</button>
