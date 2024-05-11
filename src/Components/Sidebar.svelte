<script>
  import Picture from "./Picture.svelte";
</script>

<section>
  <p>this information is on the left side bar with images</p>
  <p />
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
  section {
    flex-direction: column;
    display: flex;
    border: 4px solid black;
    padding: 10px;
    color: #9c1414;
  }
</style>
