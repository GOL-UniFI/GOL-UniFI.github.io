---
layout: page
title: Davide Pucci
<!-- subtitle: X  -->
---

<div id="main" class="clearfix">
  <div id="content" class="clearfix">
    <article class="profile">

      <header class="profile-header">
        <div class="profile-text">
          <p>
            PhD Student in <a href="https://informationengineering.dinfo.unifi.it/">Information Engineering</a>, 
            <a href="http://www.dinfo.unifi.it/" target="_blank" rel="noopener noreferrer">Department of Information Engineering (DINFO)</a>, 
            <a href="http://www.unifi.it/" target="_blank" rel="noopener noreferrer">University of Florence</a>.
          </p>

          <p>
            My research focuses on optimization techniques for mini-batch optimization and in particular to optimization techniques that are suitable to train neural-networks.
          </p>

          <div class="profile-links-img">
            <ul>
              <li><a href="https://scholar.google.it/citations?user=mc70QUkAAAAJ">Google Scholar</a></li>
              <li><a href="https://orcid.org/0000-0003-4424-9185">ORCID</a></li>
              <li><a href="https://www.linkedin.com/in/davide-pucci-44a9b3235/">LinkedIn</a></li>
              <li><a href="https://github.com/dadoPuccio">GitHub</a></li>
            </ul>

            <img src="/img/people/pucci2.jpg" 
                 alt="Pucci Davide" 
                 width="160" height="160" 
                 class="profile-photo" />
          </div>
        </div>
      </header>

      <section class="publications">
        <h2>Publications</h2>
        <ol>
          <li>
           <strong>A Globally Convergent Gradient Method with Momentum.</strong><br>
           M. Lapucci, G. Liuzzi, S. Lucidi, D. Pucci, M. Sciandrone.<br>
            <em>Computational Optimization and Applications</em> (2025). DOI: 
            <a href="https://doi.org/10.1007/s10589-025-00741-5">10.1007/s10589-025-00741-5</a>
          </li>
          <li>
          <strong> On the computation of the efficient frontier in advanced sparse portfolio optimization.</strong><br>
           A. Annunziata, M. Lapucci, P. Mansueto, D. Pucci.<br>
            <em>4OR</em> (2025). DOI: 
            <a href="https://doi.org/10.1007/s10288-025-00600-3">10.1007/s10288-025-00600-3</a>
          </li>
          <li>
          <strong> Convergence conditions for stochastic line search based optimization of over-parametrized models.</strong><br>
            M. Lapucci, D. Pucci.<br>
            <em>Optimization</em> (2025). DOI: 
            <a href="https://doi.org/10.1080/02331934.2025.2551250">10.1080/02331934.2025.2551250</a>
          </li>
          <li>
          <strong> Joint-based action progress prediction.</strong><br>
            D. Pucci, F. Becattini, A. Del Bimbo.<br>
            <em>Sensors</em> (2023). DOI: 
            <a href="https://doi.org/10.3390/s23010520">10.3390/s23010520</a>
          </li>
          <li>
          <strong> Mixed-integer quadratic programming reformulations of multi-task learning models.</strong><br>
            M. Lapucci, D. Pucci.<br>
            <em>Mathematics in Engineering</em> (2023). DOI: 
            <a href="https://doi.org/10.3934/mine.2023020">10.3934/mine.2023020</a>
          </li>
          <!-- ... altre pubblicazioni ... -->
        </ol>
      </section>

      <section class="preprints">
        <h2>Preprints</h2>
        <ol>
          <li>
          <strong> Penalty decomposition derivative free method for the minimization of partially separable functions over a convex feasible set.</strong><br>
          F Cecere, M Lapucci, D Pucci, M Sciandrone.<br>
          <em>arXiv pre-print</em> (2025). <a href="https://arxiv.org/abs/2503.21631">arXiv:2503.21631</a>
          </li>
          <li>
          <strong> Effectively Leveraging Momentum Terms in Stochastic Line Search Frameworks for Fast Optimization of Finite-Sum Problems.</strong><br>
          M Lapucci, D Pucci.<br>
          <em>arXiv pre-print</em> (2024). <a href="https://arxiv.org/abs/2411.07102">arXiv:2411.07102</a>
          </li>
          <li>
          <strong> Effective Front-Descent Algorithms with Convergence Guarantees.</strong><br>
          M. Lapucci, P. Mansueto, D. Pucci.<br>
          <em>arXiv pre-print</em> (2024). <a href="https://arxiv.org/abs/2405.08450">arXiv:2405.08450</a>
          </li>
        </ol>
      </section>

      <section class="contacts">
        <h2>Contacts</h2>
        <p>
          <a href="http://maps.google.it/maps?f=q&source=s_q&hl=it&q=via+di+santa+marta,+3,+firenze" target="_blank" rel="noopener noreferrer">
            Via di Santa Marta, 3 – 50139 Firenze (FI), Italy
          </a><br>
          E-mail: davide.pucci(AT)unifi.it
        </p>
      </section>

    </article>
  </div>
</div>

<style>
  .profile-header {
    margin-bottom: 25px;
  }

  /* 🔹 Contenitore immagine + lista (centrato) */
  .profile-links-img {
    display: flex;
    justify-content: center; /* centrato orizzontalmente */
    align-items: center;
    gap: 40px;
    margin-top: 20px;
    flex-wrap: wrap;
    text-align: left;
  }

  /* 🔹 Immagine del profilo (a sinistra su desktop) */
  .profile-photo {
    border-radius: 50%;
    object-fit: cover;
    width: 150px;
    height: 150px;
    margin: 0;
    order: -1; /* immagine a sinistra */
  }

  /* 🔹 Lista link — spostata leggermente a destra rispetto all’immagine */
  .profile-links-img ul {
    margin: 0;
    padding-left: 55px; /* margine verso destra come richiesto */
    flex: 1 1 auto;
  }

  section {
    margin-top: 40px;
  }

  h2 {
    border-bottom: 1px solid #ccc;
    padding-bottom: 4px;
  }

  a {
    color: #004c99;
  }

  /* 🔹 Mobile: immagine sopra e centrata, lista sotto */
  @media (max-width: 768px) {
    .profile-links-img {
      flex-direction: column; /* impila immagine sopra */
      align-items: center;    /* centra tutto */
      text-align: left;       /* mantiene allineamento testo coerente */
    }

    .profile-photo {
      order: 0;              /* immagine torna sopra */
      margin-bottom: 15px;
    }

    .profile-links-img ul {
      padding-left: 20px;    /* margine più stretto per mobile */
    }
  }
</style>



