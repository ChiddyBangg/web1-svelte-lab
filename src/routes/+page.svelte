<script>
  import Card from "../Components/Card.svelte";
  import RightSideBar from "../Components/RightSideBar.svelte";
  export let data;
  const people = data.people;
  console.log(data.people);
</script>

<main>
  {#each people as person}
    <Card {person} />
  {/each}
</main>

<style>
  main {
    display: flex;
    flex-wrap: wrap;
  }
</style>
