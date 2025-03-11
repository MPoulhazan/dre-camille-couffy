<script>
  import { fade } from 'svelte/transition';
</script>

<section class="hero" transition:fade>
  <div class="content">
    <h1>Dre Camille Couffy</h1>
    <p>Dentiste professionnelle dévouée à votre sourire</p>
    <button class="cta">Prendre rendez-vous</button>
  </div>
</section>

<style>
  .hero {
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
      url('/images/hero-bg.jpg') center/cover;
  }

  .content {
    text-align: center;
  }

  h1 {
    font-size: 4rem;
    margin: 0;
    color: #ffffff;
    font-weight: 700;
  }

  p {
    font-size: 1.5rem;
    margin: 1rem 0 2rem;
    color: #cccccc;
  }

  .cta {
    background-color: #00a0dc;
    color: white;
    border: none;
    padding: 1rem 2rem;
    font-size: 1.2rem;
    border-radius: 30px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  .cta:hover {
    background-color: #0082b3;
  }
</style> 