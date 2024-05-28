<script>
  import Picture from "./Picture.svelte";
  import Details from "./Details.svelte";
  export let person;
</script>

<main>
  <Picture {person}/>
  <Details {person} />
</main>
<style>

  main {
    display: flex;
    justify-content: center;  
    border: 1px solid black;
    padding: 1em;
    gap: 1em;
    background-color: lightslategray;
    grid-column: 2 / 3;
    flex:1 2;
  }
</style>
