<script>
  export let title, subtitle;
  import Link from "./Atoms/AtomLink.svelte";
</script>

<div class="max-w-sm rounded overflow-hidden shadow-lg">
  <h5 class="font-bold text-xl mb-2">{title}</h5>
  <h6 class="text-gray-700 text-base">{subtitle}</h6>
  <p class="card-text">
    Some quick example text to build on the card title and make up the bulk of
    the card's content.
  </p>
  <Link linkText="Card Link" linkURL="https://google.com" />
  <Link linkText="Another link" linkURL="https://yahoo.com" />
  <Link linkText="Test link" linkURL="https://google.com" />
</div>
