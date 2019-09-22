<script>
  export let title, subtitle;
  import Link from "./Atoms/AtomLink.svelte";
</script>

<div class="card slide-in-top">
  <div class="card-body">
    <h5 class="card-title">{title}</h5>
    <h6 class="card-subtitle mb-2 text-muted">{subtitle}</h6>
    <p class="card-text">
      Some quick example text to build on the card title and make up the bulk of the card's content.
    </p>
    <Link linkText="Card Link" linkURL="https://google.com" />
    <Link linkText="Another link" linkURL="https://yahoo.com" />
    <Link linkText="Test link" linkURL="https://google.com" />
  </div>
</div>
