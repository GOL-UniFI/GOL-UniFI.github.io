---
layout: page
title: Tesi Mansueto
permalink: /pages/theses/theses_mansueto/
---

## Logistica & mobilità urbana

<div class="row row-cols-1 row-cols-md-3 g-4 mb-4">

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-success mb-2">Green Logistics</span>
        <h5 class="card-title">Carbon-aware Vehicle Routing</h5>
        <p class="card-text">Il trasporto merci urbano è responsabile di una quota rilevante delle emissioni di CO₂, e la crescente attenzione agli obiettivi ESG ha spinto aziende e municipalità a ripensare la logistica. La tesi affronta il Green VRP: dopo una rassegna della letteratura, lo studente formulerà un modello MIP che minimizza il costo dei percorsi soggetto a un vincolo di budget sulle emissioni, applicandolo a una piccola istanza con analisi di sensitività sul budget ambientale.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + grafi &middot; CVRPLib &middot; Python / OR-Tools</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-primary mb-2">Mobilità elettrica</span>
        <h5 class="card-title">Electric Vehicle Routing Problem</h5>
        <p class="card-text">La diffusione di flotte elettriche introduce nel routing un vincolo nuovo: l'autonomia limitata della batteria e la necessità di pianificare soste di ricarica. La tesi esamina la letteratura sull'E-VRP, formula il modello MIP con variabili di stato della batteria e stazioni come nodi aggiuntivi del grafo, e lo applica a istanze standard con analisi di sensitività sull'autonomia e sul numero di stazioni.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + grafi &middot; Schneider instances &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-secondary mb-2">Smart City</span>
        <h5 class="card-title">Bike Sharing Rebalancing</h5>
        <p class="card-text">I sistemi di bike sharing soffrono di uno squilibrio strutturale tra stazioni vuote e stazioni piene. La tesi studia il problema statico di rebalancing, lo formula come problema di minimo costo su grafo, e lo applica ai dati open-source real-time di BikeMi Milano, analizzando la soluzione al variare del numero di veicoli e della capacità di trasporto.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">Flussi su grafo &middot; BikeMi open data &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

</div>

---

## Energia & smart grid

<div class="row row-cols-1 row-cols-md-2 g-4 mb-4">

  <div class="col">
    <div class="card h-100 border-success">
      <div class="card-body">
        <div class="d-flex align-items-center mb-2">
          <span class="badge badge-success mr-2">Energia</span>
          <small class="text-success font-weight-bold">⭐ più originale</small>
        </div>
        <h5 class="card-title">Ottimizzazione di una Comunità Energetica Rinnovabile (CER)</h5>
        <p class="card-text">Le CER sono state introdotte in Italia con il D.Lgs. 199/2021 e rese operative dalle regole GSE del 2024. La tesi formula un modello MIP per decidere ora per ora quando caricare e scaricare il sistema di accumulo e quanto energia scambiare con la rete, minimizzando il costo netto. Il modello viene calibrato su dati reali italiani e analizzato al variare della capacità del sistema di accumulo.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + sensitività &middot; PVGIS / GSE / GME &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-warning mb-2">Smart Grid</span>
        <h5 class="card-title">EV Charging Scheduling</h5>
        <p class="card-text">La ricarica non coordinata di veicoli elettrici rischia di generare picchi di domanda che stressano le reti di distribuzione. La tesi formula un modello MIP che decide quando e quanto ricaricare ciascun veicolo rispettando i vincoli di capacità delle colonnine e della rete, applicandolo a un piccolo caso numerico con analisi di sensitività sul numero di colonnine e sul profilo tariffario.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + scheduling &middot; Prezzi GME &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

</div>

---

## Contesti di sviluppo & crisi umanitarie

<div class="row row-cols-1 row-cols-md-2 g-4 mb-4">

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-danger mb-2">Humanitarian Logistics</span>
        <h5 class="card-title">Distribuzione di aiuti in contesti post-disastro</h5>
        <p class="card-text">Terremoti, alluvioni e conflitti generano picchi improvvisi di domanda di beni essenziali in aree con infrastrutture danneggiate. La tesi esamina la letteratura sulla logistica umanitaria, formula un modello MIP che minimizza il costo di distribuzione soggetto a vincoli di copertura minima della domanda, e lo applica a un caso ispirato a un'emergenza recente usando dati OCHA/WFP.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + grafi &middot; Dati OCHA / WFP &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-danger mb-2">Salute globale</span>
        <h5 class="card-title">Localizzazione di punti di vaccinazione in aree rurali</h5>
        <p class="card-text">L'accesso ai vaccini rimane critico in molti paesi a basso reddito, dove la popolazione è dispersa e le infrastrutture sanitarie scarse. La tesi applica il problema p-median alla localizzazione ottimale di punti di vaccinazione, minimizzando la distanza media percorsa dalla popolazione, usando dati demografici ad alta risoluzione da WorldPop.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">P-median / MIP &middot; WorldPop / OSM &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

</div>

---

## Welfare & solidarietà locale

<div class="row row-cols-1 row-cols-md-3 g-4 mb-4">

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-success mb-2">Logistica solidale</span>
        <h5 class="card-title">Raccolta e distribuzione di eccedenze alimentari</h5>
        <p class="card-text">Supermercati e mense producono ogni giorno eccedenze che potrebbero raggiungere famiglie in difficoltà, ma la logistica del recupero è complessa per via delle finestre temporali strette. La tesi formula il problema come VRP con finestre temporali, minimizzando la distanza percorsa da un veicolo che visita punti di raccolta e consegna i beni a strutture riceventi.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">VRP + finestre temp. &middot; OSM / open data &middot; Python / OR-Tools</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-success mb-2">Welfare territoriale</span>
        <h5 class="card-title">Assegnazione di utenti a punti di distribuzione assistenziale</h5>
        <p class="card-text">Le organizzazioni di welfare devono suddividere il bacino di utenza tra più punti di distribuzione minimizzando le distanze percorse da persone spesso prive di mezzi propri. La tesi applica il p-median capacitato a dati reali ISTAT di un comune italiano, studiando come cambia l'assegnazione ottimale al variare del numero di punti attivi.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">P-median capacitato &middot; Dati ISTAT / OSM &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

  <div class="col">
    <div class="card h-100">
      <div class="card-body">
        <span class="badge badge-success mb-2">Organizzazione volontariato</span>
        <h5 class="card-title">Scheduling dei turni di volontari</h5>
        <p class="card-text">Le organizzazioni di volontariato faticano a gestire l'assegnazione dei turni: disponibilità variabili, competenze diverse e coperture minime garantite. La tesi formula il problema come MIP ispirato al Nurse Scheduling Problem e analizza come la fattibilità della soluzione dipende dalla dimensione del gruppo e dalla rigidità dei vincoli di disponibilità.</p>
      </div>
      <div class="card-footer">
        <small class="text-muted">MIP + scheduling &middot; Istanza sintetica &middot; Python / PuLP</small>
      </div>
    </div>
  </div>

</div>