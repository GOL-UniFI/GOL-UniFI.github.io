---
layout: page
title: Matteo Lapucci
<!-- subtitle: X  -->
---

<div id="main" class="clearfix">
  <div id="content" class="clearfix">
    <article class="profile">

      <header class="profile-header">
        <div class="profile-text">
          <p>
            RTD/A Assistant Professor at, 
            <a href="http://www.dinfo.unifi.it/" target="_blank" rel="noopener noreferrer">Department of Information Engineering (DINFO)</a>, 
            <a href="http://www.unifi.it/" target="_blank" rel="noopener noreferrer">University of Florence</a>
          </p>

          <p>
            My research focuses on the development of algorithms for nonlinear optimization in various setups - unconstrained, constrained, multi-objective, black-box - and the application of optimization methods in machine learning, statistics and data science in general.
            I also deal with mixed-integer optimization models and tools for addressing scheduling and planning tasks from real-world use cases. 
          </p>

          <div class="profile-links-img">
            <ul>
              <li><a href="https://scholar.google.com/citations?user=qxaPTogAAAAJ&hl=it&oi=ao">Google Scholar profile</a></li>
            </ul>

            <img src="/img/people/ML-sito.JPG" 
                 alt="Matteo Lapucci" 
                 width="160" height="160" 
                 class="profile-photo" />
          </div>
        </div>
      </header>

      <section class="publications">
        <h2>Publications</h2>
        <p>For an updated list of publications see my  <a href="[http://www.dinfo.unifi.it/](https://scholar.google.com/citations?user=eOflrC8AAAAJ&hl=it&oi=ao)">Google Scholar page</a></p>
        </section>

      
      <section class="contacts">
        <h2>Contacts</h2>
        <p>
          <a href="http://maps.google.it/maps?f=q&source=s_q&hl=it&q=via+di+santa+marta,+3,+firenze" target="_blank" rel="noopener noreferrer">
            Via di Santa Marta, 3 – 50139 Firenze (FI), Italy
          </a> - Room 241, second floor<br>
          E-mail: matteo.lapucci at unifi.it
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


