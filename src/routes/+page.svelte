<script>
  import Card from '../Components/Card.svelte'
  import Footer from '../Components/Footer.svelte';
  import Header from '../Components/Header.svelte';
  
</script>
<Header />

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<section>
    <Card />
    <Card />
</section>
<left-side />
<Footer />
<style>
    section{
        display: flex;
     }
</style>
