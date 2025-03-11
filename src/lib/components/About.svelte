<section class="about">
  <h2>À Propos</h2>
  <div class="content">
    <div class="image">
      <img src="/images/doctor.jpg" alt="Dre Camille Couffy" />
    </div>
    <div class="text">
      <h3>Dre Camille Couffy</h3>
      <p>
        Je suis le Docteur Camille Couffy, dentiste généraliste à Montréal. En 2021, j'ai décidé de
        m'installer au Canada pour enrichir ma carrière et offrir mes compétences à une nouvelle
        communauté.
      </p>
      <p>
        Après avoir complété mon équivalence à Boucherville pendant un an, j'ai choisi de
        m'installer à Montréal, une ville vibrante et accueillante.
      </p>
      <p>
        Ma priorité en tant que dentiste est de m'assurer que mes patients se sentent à l'aise et en
        confiance. J'aime particulièrement tisser des liens avec chacun de mes patients et les
        accompagner vers une santé bucco-dentaire optimale. Passionnée par toutes les facettes de la
        médecine dentaire, j'offre des soins complets et personnalisés, allant de la prévention aux
        traitements plus complexes.
      </p>
      <p>
        Je suis ravie de faire partie de l'équipe de la Clinique Dentaire Malka et j'ai hâte de vous
        rencontrer pour vous aider à obtenir le sourire sain et éclatant que vous méritez.
      </p>
      <ul>
        <li class="credentials">Formation à la faculté de chirurgie dentaire de Nantes</li>
        <li class="credentials">Membre de l'ordre des dentistes du Québec</li>
      </ul>
    </div>
  </div>
</section>

<style>
  .about {
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
    align-items: center;
  }

  .image {
    display: flex;
    justify-content: center;
  }

  .image img {
    width: 50%;
    border-radius: 10px;
    box-shadow: 0 0 20px rgba(0, 160, 220, 0.2);
  }

  .text h3 {
    font-size: 2rem;
    margin-bottom: 1rem;
  }

  .text p {
    line-height: 1.6;
    color: #cccccc;
  }

  ul {
    list-style: none;
    padding: 0;
    margin-top: 1.5rem;
  }

  li {
    margin: 0.5rem 0;
    color: #cccccc;
  }

  li.credentials {
    font-style: italic;
    text-align: right;
    margin: 0.5rem 0;
    color: #cccccc;
  }

  @media (max-width: 768px) {
    .content {
      grid-template-columns: 1fr;
    }
  }
</style>
