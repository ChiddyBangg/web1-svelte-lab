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
<left-side>
  <p>this information is on the left side bar with images</p>

  <Picture />
  <ul>
    <li><a href="link 1 ">Link 1</a></li>
    <li><a href="link 2">Link 2</a></li>
    <li><a href="link 3">Link 3</a></li>
 
  </ul>
</left-side>



<style>
  ul {
    padding-left: 0;
  }
  li {
    list-style: none;
  }


  left-side {
    grid-column: 1 / 2;
    padding-right: 1em;
  }
  
</style>
