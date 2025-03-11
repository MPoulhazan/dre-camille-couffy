<script>
  import Hero from '$lib/components/Hero.svelte';
  import About from '$lib/components/About.svelte';
  import Services from '$lib/components/Services.svelte';
  import Contact from '$lib/components/Contact.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<main>
  <Hero />
  <About />
  <Services />
  <Contact />
  <Footer />
</main>

<style>
  :global(body) {
    background-color: #0a0a0a;
    color: #ffffff;
    font-family: 'Inter', sans-serif;
    margin: 0;
    padding: 0;
  }

  :global(*) {
    box-sizing: border-box;
  }

  main {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
  }
</style> 