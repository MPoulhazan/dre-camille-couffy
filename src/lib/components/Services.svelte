<section class="services">
  <h2>Mes Services</h2>
  <div class="grid">
    <div class="service-card">
      <i class="fas fa-tooth"></i>
      <h3>Soins Préventifs</h3>
      <p>Examens, nettoyages et conseils personnalisés pour maintenir une excellente santé bucco-dentaire.</p>
    </div>
    <div class="service-card">
      <i class="fas fa-smile"></i>
      <h3>Esthétique Dentaire</h3>
      <p>Blanchiment, facettes et autres traitements pour un sourire éclatant.</p>
    </div>
    <div class="service-card">
      <i class="fas fa-teeth"></i>
      <h3>Restaurations</h3>
      <p>Obturations, couronnes et ponts utilisant les meilleurs matériaux.</p>
    </div>
  </div>
</section>

<style>
  .services {
    padding: 5rem 0;
  }

  h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #00a0dc;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
  }

  .service-card {
    background: rgba(255, 255, 255, 0.05);
    padding: 2rem;
    border-radius: 10px;
    text-align: center;
    transition: transform 0.3s;
  }

  .service-card:hover {
    transform: translateY(-5px);
  }

  .service-card i {
    font-size: 3rem;
    color: #00a0dc;
    margin-bottom: 1rem;
  }

  .service-card h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }

  .service-card p {
    color: #cccccc;
    line-height: 1.6;
  }
</style> 