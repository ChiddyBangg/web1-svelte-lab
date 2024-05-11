<script>
  import Card from "../Components/Card.svelte";
  import Footer from "../Components/Footer.svelte";
  import Header from "../Components/Header.svelte";
  import Sidebar from "../Components/Sidebar.svelte";
</script>

<Header />

<section>
  <Sidebar />
  <Card />
  <Card />
  <Card />
</section>

<Footer />

<style>
  section {
    display: flex;
  }
</style>
