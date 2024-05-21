<script>
  import Picture from "./Picture.svelte";
  import Details from "./Details.svelte";
</script>

<main>
<section>
  <Picture />
  <Details />
</section>
</main>
<style>
  section {
    display: flex;
    padding: 10px;
    height: 100 ;
    border: 1px solid black;
    padding: 1em;
    gap: 1em;
    background-color: lightslategray;
  }
  main {
    grid-column: 2 / 3;
  }
</style>
