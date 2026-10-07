  <div id="main" class="clearfix">
  <div id="content" class="clearfix">
  <article class="profile">
  <header class="profile-header">
    <div class="profile-text">
      <p>
        PhD Student in <a href="https://informationengineering.dinfo.unifi.it/">Information Engineering</a>, 
        <a href="http://www.dinfo.unifi.it/" target="_blank" rel="noopener noreferrer">Department of Information Engineering (DINFO)</a>, 
        <a href="http://www.unifi.it/" target="_blank" rel="noopener noreferrer">University of Florence</a>.
        <a href="https://www.morfodesign.it/" target="_blank" rel="noopener noreferrer">Morfo Design srl</a>
      </p>

      <p>
        My research focuses on Machine Learning and Optimization Methods for Leveraging industrial Data Lakes.
      </p>

      <div class="profile-links-img">
        <ul>
          <li><a href="https://orcid.org/0009-0002-7433-9587">ORCID</a></li>
          <li><a href="https://www.linkedin.com/in/francesco-bellezza-927083341">LinkedIn</a></li>
          <li><a href="https://github.com/MasterHope">GitHub</a></li>
        </ul>

        <img src="/img/people/Bellezza.jpg" 
             alt="Bellezza Francesco" 
             width="160" height="160" 
             class="profile-photo" />
      </div>
    </div>
  </header>

  <!-- <section class="preprints">
    <h2>Preprints</h2>
    <ol>
      <li>
      <strong> TITLE.</strong><br>
      Authors <br>
      <em>arXiv pre-print</em> (2026). <a href="https://arxiv.org">arXiv:xxxx.xxxx</a>
      </li>
    </ol>
  </section> -->

  <section class="contacts">
    <h2>Contacts</h2>
    <p>
      <a href="http://maps.google.it/maps?f=q&source=s_q&hl=it&q=via+di+santa+marta,+3,+firenze" target="_blank" rel="noopener noreferrer">
        Via di Santa Marta, 3 – 50139 Firenze (FI), Italy
      </a><br>
      E-mail: francesco.bellezza(AT)unifi.it
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



