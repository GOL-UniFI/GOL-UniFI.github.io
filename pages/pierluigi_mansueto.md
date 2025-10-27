---
layout: page
title: Pierluigi Mansueto
<!-- subtitle: X  -->
---

<div id="main" class="clearfix">
  <div id="content" class="clearfix">
    <article class="profile">

      <header class="profile-header">
        <div class="profile-text">
          <p>
            PhD in <a href="https://informationengineering.dinfo.unifi.it/">Information Engineering</a>, 
            <a href="http://www.dinfo.unifi.it/" target="_blank" rel="noopener noreferrer">Department of Information Engineering (DINFO)</a>, 
            <a href="http://www.unifi.it/" target="_blank" rel="noopener noreferrer">University of Florence</a>.
          </p>

          <p>
            My research interests are optimization applications, machine learning, and other related topics. 
            My principal addressed problems concern multi-objective optimization, clustering, and Bayesian optimization.
          </p>

          <div class="profile-links-img">
            <ul>
              <li><a href="https://scholar.google.com/citations?user=5dwG9b8AAAAJ&amp;hl=it">Google Scholar profile</a></li>
              <li>ORCID: <a href="https://orcid.org/0000-0002-1394-0937">0000-0002-1394-0937</a></li>
              <li><a href="/files/docs/CV-Pierluigi-Mansueto.pdf">Curriculum Vitae (PDF)</a></li>
              <li>PhD Thesis available <a href="https://flore.unifi.it/retrieve/9b40e7bf-1fa0-40ef-a5dc-fb8ca9303f15/PhD-Thesis_Mansueto.pdf">here</a>.</li>
            </ul>

            <img src="/img/people/mansueto.jpeg" 
                 alt="Pierluigi Mansueto" 
                 width="160" height="160" 
                 class="profile-photo" />
          </div>
        </div>
      </header>

      <section class="publications">
        <h2>Publications</h2>
        <ol>
          <li>
            On the computation of the efficient frontier in advanced sparse portfolio optimization.<br>
            <strong>A. Annunziata, M. Lapucci, P. Mansueto, D. Pucci</strong>.<br>
            <em>4OR</em> (2025). DOI: 
            <a href="https://doi.org/10.1007/s10288-025-00600-3">10.1007/s10288-025-00600-3</a>
          </li>
          <!-- ... altre pubblicazioni ... -->
        </ol>
      </section>

      <section class="preprints">
        <h2>Preprints</h2>
        <ol>
          <li>
            A Nonmonotone Front Descent Method for Bound-Constrained Multi-Objective Optimization.<br>
            <strong>P. Mansueto</strong>.<br>
            <em>ArXiv pre-print</em> (2025). DOI:
            <a href="https://doi.org/10.48550/arXiv.2509.02409">10.48550/arXiv.2509.02409</a>
          </li>
          <!-- ... altri preprint ... -->
        </ol>
      </section>

      <section class="talks">
        <h2>Talks</h2>
        <ul>
          <li><a href="https://europt2025.org/">EUROPT 2025, Southampton</a> — Combining Gradient Information and Primitive Directions for High-Performance Mixed-Integer Optimization</li>
          <!-- ... altri talk ... -->
        </ul>
      </section>

      <section class="software">
        <h2>Software</h2>
        <ul>
          <li>fpd_nmt v1.0.0 — <a href="https://github.com/pierlumanzu/fpd_nmt">github.com/pierlumanzu/fpd_nmt</a></li>
          <!-- ... altri software ... -->
        </ul>
      </section>

      <section class="contacts">
        <h2>Contacts</h2>
        <p>
          <a href="http://maps.google.it/maps?f=q&source=s_q&hl=it&q=via+di+santa+marta,+3,+firenze" target="_blank" rel="noopener noreferrer">
            Via di Santa Marta, 3 – 50139 Firenze (FI), Italy
          </a><br>
          E-mail: pierluigi.mansueto@unifi.it, pierluigimansueto@gmail.com
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



