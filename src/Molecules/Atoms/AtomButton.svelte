<script>
  export let text,
    size = "medium", // small, medium, large
    type = "default", // default, outline, flat
    color = "primary"; // color - primary, secondary

  let colorClass = "btn-" + color;

  let sizeClass =
    size === "small" ? " btn-sm" : size === "large" ? " btn-lg" : "";

  let typeClass =
    type === "outline"
      ? "btn-outline-" + color
      : type === "flat"
      ? "btn-flat"
      : colorClass;
</script>

<button type="button" class="btn {typeClass}{sizeClass} blue-border-hover">{text}</button>
