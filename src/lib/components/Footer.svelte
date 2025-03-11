<footer>
  <div class="content">
    <div class="logo">
      <h3>Dre Camille Couffy</h3>
      <p>Votre sourire, notre priorité</p>
    </div>

    <div class="social">
      <a
        href="https://www.linkedin.com/in/camille-couffy-392a421b1/"
        aria-label="LinkedIn de Dre Camille Couffy"
      >
        <i class="fab fa-linkedin"></i>
      </a>
    </div>
  </div>

  <div class="bottom">
    <p>&copy; {new Date().getFullYear()} Dre Camille Couffy. Tous droits réservés.</p>
  </div>
</footer>

<style>
  footer {
    background: rgba(255, 255, 255, 0.05);
    padding: 3rem 0 1rem;
    margin-top: 5rem;
  }

  .content {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .logo h3 {
    font-size: 1.5rem;
    margin: 0;
  }

  .logo p {
    color: #cccccc;
    margin: 0.5rem 0;
  }

  .social {
    display: flex;
    gap: 1rem;
  }

  .social a {
    color: #00a0dc;
    font-size: 1.5rem;
    transition: color 0.3s;
  }

  .social a:hover {
    color: #0082b3;
  }

  .bottom {
    text-align: center;
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid rgba(255, 255, 255, 0.1);
  }

  .bottom p {
    color: #cccccc;
    font-size: 0.9rem;
  }
</style>
