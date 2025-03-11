<section class="contact">
  <h2>Contact</h2>
  <div class="content">
    <div class="info">
      <h3>Informations</h3>
      <p><i class="fas fa-phone"></i>(514) 388-3368</p>
      <p><i class="fas fa-envelope"></i> dre.camille.couffy@gmail.com</p>
      <p>
        <i class="fas fa-map-marker-alt"></i>Cabinet Malka,8131 R. Saint-Denis, Montréal, QC H2P 2G7
      </p>

      <div class="hours">
        <h4>Horaires</h4>
        <p>Lundi, Mardi, Mercredi: 9h - 19h</p>
      </div>
    </div>

    <form class="contact-form">
      <input type="text" placeholder="Nom complet" required />
      <input type="email" placeholder="Email" required />
      <input type="tel" placeholder="Téléphone" required />
      <textarea placeholder="Message" rows="5" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </div>
</section>

<style>
  .contact {
    padding: 5rem 0;
  }

  h2 {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #00a0dc;
  }

  .content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
  }

  .info {
    background: rgba(255, 255, 255, 0.05);
    padding: 2rem;
    border-radius: 10px;
  }

  .info h3 {
    font-size: 1.8rem;
    margin-bottom: 1.5rem;
  }

  .info p {
    margin: 1rem 0;
    color: #cccccc;
  }

  .info i {
    color: #00a0dc;
    margin-right: 1rem;
  }

  .hours {
    margin-top: 2rem;
  }

  .hours h4 {
    font-size: 1.2rem;
    margin-bottom: 1rem;
  }

  .contact-form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
  }

  input,
  textarea {
    padding: 1rem;
    background: rgba(255, 255, 255, 0.05);
    border: 1px solid rgba(255, 255, 255, 0.1);
    border-radius: 5px;
    color: white;
  }

  button {
    background-color: #00a0dc;
    color: white;
    border: none;
    padding: 1rem;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s;
  }

  button:hover {
    background-color: #0082b3;
  }

  @media (max-width: 768px) {
    .content {
      grid-template-columns: 1fr;
    }
  }
</style>
