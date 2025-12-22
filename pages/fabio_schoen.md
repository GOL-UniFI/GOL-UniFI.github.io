---
layout: page
title: Fabio Schoen
<!-- subtitle: X  -->
---

<div id="main" class="clearfix">
  <div id="content" class="clearfix">
    <article class="profile">

      <header class="profile-header">
        <div class="profile-text">
          <p>
            Professor Emeritus, previously at
            <a href="http://www.dinfo.unifi.it/" target="_blank" rel="noopener noreferrer">Department of Information Engineering (DINFO)</a>, 
            <a href="http://www.unifi.it/" target="_blank" rel="noopener noreferrer">University of Florence</a>
          </p>
		  <p>
		  Adjoint Professor of Linear Algebra at
		  <a href="https://www.nyu.edu/florence.html"
          target="_blank" >New York University, Florence</a>
		  </p>
		  <p>(previously: adjoint professor of Operations Management)</p>
          <div class="profile-links-img">

            <img src="/img/people/fabioschoen.png" 
                 alt="Fabio Schoen" 
                 width="160" height="160" 
                 class="profile-photo" />
          </div>

          <p>
            My research focused on 
            <ol>
            <li>Global Optimization: models, methods applications</li>
			<li>Applications of Operations Research</li>
            </ol>  
          </p>

          
        </div>
      </header>

      <section class="publications">
        <h2>Publications</h2>
        <p>For an updated list of publications see my  <a
		href="https://scholar.google.com/citations?user=wYmt8csAAAAJ&hl=en">Google
		Scholar page</a></p> 
		<p>
		Besides papers, I have been the author of a few books:
		<ol>
		<li><a
		href="https://fabioschoen.github.io/OptimizationModels//">Optimization
		Models (2024)</a>. Available both as a free on line
		textbook, as well as a printed hard copy one.</li>
		<li><a
		href="https://epubs.siam.org/doi/10.1137/1.9781611972672">Global
		Optimization: Theorym Algorithms and Applications</a>,
		MOS-SIAM Series on Optimizaiton (2013)</li>
		<li><a
		href="https://www.amazon.it/Fondamenti-Ricerca-Operativa-Fabio-Schoen/dp/1542342023/ref=asc_df_1542342023?mcid=c1f4143c8b9836d08c90a891ef667a67&tag=googshopit-21&linkCode=df0&hvadid=700838296692&hvpos=&hvnetw=g&hvrand=10814749066914180055&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9198557&hvtargid=pla-371584716643&psc=1&hvocijid=10814749066914180055-1542342023-&hvexpln=0">
		Fondamenti di Ricerca Operativa</a>, Amazon (2017)</li>
		</ol>
		</p>
		<p>
		I have also been a co-founder of two startups:
		<ol>
		<li> KKT srl, founded in 2011 as a Startup of the University
		of Florence, later acquired by Fleetmatics, now part of <a
		href="https://www.verizonconnect.com/">Verizon Connect</a>
		</li>
		<li><a href="https://intuendi.com/">Intuendi srl</a>, born in
		2016, specialized in demand planning for the supply chain
		</li>
		</ol>
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


