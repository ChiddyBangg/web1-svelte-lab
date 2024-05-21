<script>
import Picture from "./Picture.svelte";
</script>



<right-side>
    <p>this information is on the Right side bar with images</p>
  
    <Picture />
    <ul>
      <li><a href="link 1 ">Link 1</a></li>
      <li><a href="link 2">Link 2</a></li>
      <li><a href="link 3">Link 3</a></li>
    
    </ul>
  </right-side>




<style>  right-side {
    grid-column: 3 / 4;
}
ul {
    padding-left: 0;
  }
  li {
    list-style: none;
  }
  </style>