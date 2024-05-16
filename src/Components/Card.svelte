<script>
  import Picture from "./Picture.svelte";
  import Details from "./Details.svelte";
</script>

<section>
  <Picture />
  <Details />
</section>

<style>
  section {
    display: flex;
    padding: 10px;
    height: 250;
    border: 1px solid black;
    padding: 1em;
    gap: 1em;
  }
</style>
