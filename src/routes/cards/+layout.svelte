<script>
    import Sidebar from "../../Components/Sidebar.svelte";

let nav = [
    { text: "Home", href: "/" },
    { text: "Manage Cards ", href: "/cards/mange-cards" },
    { text: "View cards", href: "/cards/view-cards" },
   
    // { text: "Contact", href: "/contact" },
  ];

</script>

<Sidebar navItems={nav} />
<section>
  <slot />
  <p>every page in the cards</p>
</section>

<style>
  section {
    border:
      1px,
      dotted purple;
  }
</style>
