<script>
  function setColor(colorName) {
    newColor = colorName;
  }
  import msg from "../tailwind.config.js";
  let newColor = "orange";

  export let className =
      "font-bold py-2 px-4 rounded text-base bg-{newColor}-600",
    text = "Test button";

  // console.log("New: " + msg.theme.colors);
  //   if (msg.theme.colors.hasOwnProperty('id')) {
  //      console.log("New: " + msg.theme.colors);
  // }
  let colorList = [];

  Object.keys(msg.theme.colors).forEach(prop => {
    // if (msg.theme.colors[prop].hasOwnProperty("100"))

    // console.log(msg.theme.colors[prop]);

    colorList.push(prop);
    console.log(prop);
    console.log(msg.theme.colors[prop]);
  });

  // var size = Object.keys(msg.theme.colors).length;
  // console.log(size);

  // o.hasOwnProperty("100"); // returns true

  // const peopleArray = Object.keys(const peopleArray = Object.keys(peopleObj).map(i => peopleObj[i])).map(i => peopleObj[i])
</script>

<div class="bg-gray-800 h-screen text-white">
  <div />
  <button type="button" class={className}>{text}</button>
  <!-- grouped radio inputs are mutually exclusive -->
  <!-- <input type="radio" bind:group={tortilla} value="Plain" /> -->
  <br />
  Background color:
  {#each colorList as {}, i}
    <input
      type="radio"
      name="gender"
      value="male"
      onChange="setColor( colorList[i])" />
    {colorList[i]}
  {/each}

  <br />
</div>
