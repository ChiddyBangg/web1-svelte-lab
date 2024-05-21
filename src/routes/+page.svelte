<script>
  import Card from "../Components/Card.svelte";
  import Footer from "../Components/Footer.svelte";
  import Header from "../Components/Header.svelte";
  import Sidebar from "../Components/Sidebar.svelte";
  import RightSideBar from "../Components/RightSideBar.svelte";

  let nav = [
    { text: "Home", href: "/" },
    { text: "About", href: "/about" },
    { text: "My Cards", href: "/cards" },
    { text: "Contact", href: "/contact" },
  ];
</script>

<Header />

<main> 
    <Sidebar navItems={nav} />
  <section>
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />
    <Card />      
  </section>
    <RightSideBar />
</main>
  <Footer />

<style>
  section {
    display: flex;
    flex-wrap: wrap;
    gap: 1em;
  }
 
  
  main {
    
    
    display: grid;
    grid-template: auto 1fr auto / auto 1fr auto;
  }
</style>
