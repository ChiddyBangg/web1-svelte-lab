<script>
  import Footer from "../Components/Footer.svelte";
  import Header from "../Components/Header.svelte";
  import Sidebar from "../Components/Sidebar.svelte";

  let nav = [
    { text: "Home", href: "/" },
    { text: "Profile ", href: "/profile" },
    { text: "Cards", href: "/cards" },
    // { text: "Contact", href: "/contact" },
  ];
</script>

<Header />

<main>
     <!-- <Sidebar navItems={nav} />  -->
  <slot />
</main>
<Footer />

<style>
  main {
    display: flex;
    grid-template: auto 1fr auto / auto 1fr;
  }
</style>
