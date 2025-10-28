---
layout: page
title: Federica Donnini
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
            My research interests are optimization techniques and humanitarian logistics applications.
            I have mainly worked on stochastic optimization problems, with a focus on Benders decomposition and the K-adaptability approach.
          </p>

          <div class="profile-links-img">
            <ul>
              <li><a href="https://scholar.google.com/citations?user=BPyV6xoAAAAJ&hl=en&oi=ao">Google Scholar profile</a></li>
              <li>ORCID: <a href="https://orcid.org/0009-0004-0377-2046">0000-0002-1394-0937</a></li>
            </ul>

            <img src="/img/people/donnini2.jpg" 
                 alt="Federica Donnini" 
                 width="160" height="160" 
                 class="profile-photo" />
          </div>
        </div>
      </header>

    <section class="publications">
    <h2>Publications</h2>
    <ol>
    </ol>
    </section>

    <section class="preprints">
    <h2>Preprints</h2>
    <ol>
        <li>
        <strong>Efficient globalization of heavy-ball type methods for unconstrained optimization based on curve searches.</strong><br>
        F. Donnini, M. Lapucci, P. Mansueto.<br>
        <em>ArXiv pre-print</em> (2025). DOI: <a href="https://doi.org/10.48550/arXiv.2505.19705">10.48550/arXiv.2505.19705</a>
        </li>
    </ol>
    </section>


      <section class="talks">
        <h2>Talks</h2>
        <ul>

        <li>
        <a href="https://euroyoung.eu/naples2025/">EUROYoung Workshop 2025, Naples</a> — On K-adaptability for two-stage stochastic programs
        </li>

        <li>
        <a href="https://www.airoconference.it/ods2025/">ODS 2025, Milan</a> — A partition-based method for K-adaptability in two-stage stochastic optimization
        </li>

        </ul>
      </section>

      <section class="software">
        <h2>Software</h2>
        <ul>

        <li>cs_hb v1.0.0 — <a href="https://github.com/dfede3/cs_hb">github.com/dfede3/cs_hb</a></li>

        </ul>
      </section>

      <section class="contacts">
        <h2>Contacts</h2>
        <p>
          <a href="http://maps.google.it/maps?f=q&source=s_q&hl=it&q=via+di+santa+marta,+3,+firenze" target="_blank" rel="noopener noreferrer">
            Via di Santa Marta, 3 – 50139 Firenze (FI), Italy
          </a><br>
          E-mail: federica dot donnini at unifi dot it
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



