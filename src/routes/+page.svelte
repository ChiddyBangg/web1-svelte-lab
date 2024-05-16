<script>
  import Card from "../Components/Card.svelte";
  import Footer from "../Components/Footer.svelte";
  import Header from "../Components/Header.svelte";
  import Sidebar from "../Components/Sidebar.svelte";

  let nav = [
    { text: "Home", href: "/" },
    { text: "About", href: "/about" },
    { text: "My Cards", href: "/cards" },
    { text: "Contact", href: "/contact" },
  ];
</script>

<Header />
<Sidebar navItems={nav} />
<section>
  <Card />
  <Card />
  <Card />
</section>

<Footer />

<style>
  section {
    display: flex;
    gap: 1em;
  }
</style>
