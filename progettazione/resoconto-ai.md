## Sessione 1

* **Che cosa ho chiesto:** Ho chiesto spiegazioni sulla struttura della consegna, il completamento dei file dati (`sedi.json` ed `eventi.json`), la stesura della documentazione tecnica (`dati/SCHEMA.md` con diagramma Mermaid), il codice JavaScript con `fetch` per rendere dinamico `programma.html` e l'integrazione dell'API Open-Meteo in `info.html`.
* **Che cosa ho usato, modificato o scartato:** Ho utilizzato la struttura dei JSON, la scheda tecnica con schema ER in Mermaid, lo script `fetch` per la generazione automatica delle card degli eventi e la chiamata API per il meteo in tempo reale. Ho invece modificato manualmente i percorsi delle immagini e i titoli in `eventi.json` e integrato il codice HTML/JS della sezione meteo all'interno della mia pagina `info.html` esistente (mantenendo galleria Swiper e mappa uMap).
* **Come ho verificato:** Ho controllato la formattazione di `SCHEMA.md` tramite l'anteprima di Visual Studio Code e testato il funzionamento dinamico di `programma.html` e `info.html` nel browser tramite Live Server, verificando il caricamento dei dati, l'associazione corretta tra `sede_id` e nome della sede e l'aggiornamento live di temperatura, vento e orario.
* **Problemi avuti e come li ho risolti:** 
  * *Immagini non visibili in `programma.html`:* inizialmente i nomi dei file `.svg` ipotizzati dall'AI in `eventi.json` (es. `la-citta-in-un-manifesto.svg`) non coincidevano con quelli reali nella cartella `assets/`; li ho confrontati con i file locali e aggiornati nel JSON.
  
