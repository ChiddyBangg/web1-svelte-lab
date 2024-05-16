<script>
  import Picture from "./Picture.svelte";
  export let navItems;
</script>

<nav>
  <ul>
    {#each navItems as item}
      <li><a href={item.href}>{item.text}</a></li>
    {/each}
  </ul>
</nav>
<section>
  <p>this information is on the left side bar with images</p>

  <Picture />
  <ul>
    <li><a href="link 1 ">Link 1</a></li>
    <li><a href="link 2">Link 2</a></li>
    <li><a href="link 3">Link 3</a></li>
    <li><a href="link 1 ">Link 1</a></li>
    <li><a href="link 2">Link 2</a></li>
    <li><a href="link 3">Link 3</a></li>
    <li><a href="link 1 ">Link 1</a></li>
    <li><a href="link 2">Link 2</a></li>
    <li><a href="link 3">Link 3</a></li>
    <li><a href="link 1 ">Link 1</a></li>
    <li><a href="link 2">Link 2</a></li>
    <li><a href="link 3">Link 3</a></li>
  </ul>
</section>

<style>
  ul {
    padding-left: 0;
  }
  li {
    list-style: none;
  }
  section {
    float: left;
    flex-direction: column;
    display: flex;
    border: 4px solid black;
    padding: 10px;
    color: #9c1414;
  }
</style>
