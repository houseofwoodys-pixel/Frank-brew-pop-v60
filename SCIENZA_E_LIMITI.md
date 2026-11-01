# Frank’s V60 · Brew Science v5

## Perché non esiste una formula affidabile «dose + macinatura → tempo finale»

*The Physics of Filter Coffee* di Jonathan Gagné (2020) è una trattazione dei meccanismi di **trasporto, diffusione e flusso attraverso letti porosi**, non una tabella di secondi per ogni V60. Il modello di Darcy richiederebbe almeno permeabilità effettiva del letto, geometria, distribuzione dimensionale delle particelle, viscosità, pressione idrostatica e la possibilità di bypass, dati che il calcolatore non osserva. Altri processi come migrazione dei fini, clogging e canalizzazione cambiano la permeabilità durante la preparazione. Assegnare a queste cause un «+12 s» fisso sarebbe falsa precisione.

Di conseguenza, Frank’s V60 differenzia **quantità e tempi del programma di versamento** (calcolabili) da **durata del drenaggio** (osservabile, non deducibile). Il benchmark iniziale 2:30–3:30 per 15 g/250 g rimane una scelta sperimentale dell’app e non è dichiarato scientificamente ottimale. Per ricette diverse, lo spostamento del benchmark è effettuato solo sulla variazione della fine dell’ultima versata programmata, con fascia più larga per quantità estreme. Con almeno tre tazze piacevoli dello stesso caffè/lotto e stessi parametri, la fascia passa a una mediana empirica e una dispersione descrittiva; non rappresenta un intervallo di confidenza o una causalità.

## Relazioni introdotte o corrette

| Aspetto | Principio tratto dai testi | Comportamento nell'app e limite |
|---|---|---|
| Diffusione vs advezione | Gagné, cap. 1 pp. 5–12: solubili con cinetiche differenti e fini che modificano l'estrazione | Non presume estrazione proporzionale ai minuti trascorsi; il tempo isolato non classifica la tazza |
| Resa media e uniformità | Gagné, cap. 1 pp. 1–4 e 14–17: stessa EY media può mascherare estrazione irregolare | Diagnosi sensoriale considera bagnatura, flusso e gusto; non usa EY come voto al gusto |
| EY da TDS | Gagné, cap. 1 pp. 14–17; Lingle, cap. 2 | `TDS% × bevanda_g / dose_g` è la **resa apparente nella bevanda**. Non quantifica il contenuto solubile residuo nel liquido trattenuto dal letto; la vera media del letto non è ricavabile senza altre misure |
| Macinatura e fini | Gagné, cap. 3 pp. 45–70 | Molti fini possono aumentare l'estrazione e contemporaneamente intasare il filtro; nessuna equivalenza in click Fellow Opus |
| Permeabilità e canali | Gagné, cap. 4 pp. 71–104 | Registrazione opzionale del flusso e attenzione a canalizzazione e migrazione fini; nessun coefficiente inventato tempo/grammi |
| Filtri, intasamento | Gagné, cap. 5 pp. 105–126, in particolare p. 113 | Il consiglio privilegia una prova con meno swirl o, successivamente, grana appena più grossa; una variabile per volta |
| Getto, altezza e agitazione | Gagné, cap. 6 pp. 127–144 | Bagnatura uniforme, non colpire sempre un punto o le pareti; swirl leggero utile ma potenzialmente negativo con molti fini |
| Bypass nel V60 | Gagné, cap. 7 pp. 145–158 (grafico p. 148) | Controllare aderenza del filtro e cucitura; flusso rapido non è sinonimo di sottoestrazione |
| Effetto termico del dripper | Gagné, cap. 7 p. 152 | Selezione materiale V60 e note sul preriscaldamento; **nessuna** conversione fittizia °C bollitore → °C letto |
| Preinfusione / bloom | Gagné, cap. 4 p. 88 e cap. 10 pp. 191, 196–197 | 45 s come riferimento, più lungo per alcune chiare e più corto per scure: sono convenzioni operative basate sulla direzione dei fattori, non tempi garantiti |
| Temperatura e tostatura | Gagné, cap. 10 p. 194; Lingle cap. 1 e 6 | Due profili: conservativo (96/94/92 °C) e ispirato a Gagné (99/94/88 °C). Valore medio 94 °C **scelta dell’app**. Non sono ottimi provati per tutti i chicchi |
| Forza vs resa | Gagné, cap. 10 p. 194; Lingle cap. 1 | Tazza «acquosa» può richiedere rapporto più concentrato, non necessariamente macinatura più fine; gusto ed EY sono distinti |
| Acqua | Gagné, cap. 2 pp. 21–25, 35 | Alcalinità (tampone acidità), durezza (ioni) e TDS totale sono separati; non vengono predette correzioni di ricetta dal solo TDS |
| Differenze fra caffè | Gagné, cap. 9 pp. 167–184 | Nome/lotto obbligatorio per registrare la storia dei tempi «buoni». Non mescoliamo caffè diversi nello storico |

## Cosa **non** pretende di fare

- Non ricostruisce una distribuzione granulometrica dai numeri «fine / medio / grosso» o dai click del macinacaffè.
- Non stima numericamente la resa di estrazione senza rifrattometro.
- Non ricostruisce il drenaggio da equazioni di Darcy con parametri ignoti.
- Non attribuisce uno score di «sovraestratto / sottoestratto» sulla sola durata.
- Non trasmette dati a Notion e non possiede connessioni a Notion; i riferimenti restano nello storage di questo browser/dispositivo, che può essere cancellato dal sistema o dall’utente.
- Non fornisce un tempo a cui interrompere il flusso. Se il filtro è completamente intasato, decidi osservando la preparazione anziché prendere il limite della fascia come comando.

## Come validare la funzione su un vero caffè

Con lo stesso caffè e lo stesso filtro, prepara una serie di V60 registrando dose, acqua, temperatura, macinatura relativa, livello di bagnatura, flusso, tempo di drenaggio e sensazioni. Mantieni fissi quasi tutti i parametri e cambia **una** variabile per volta. Segna le prove piacevoli: da almeno tre osservazioni confrontabili avrai un benchmark interno più rilevante della fascia standard. Se vuoi una misura quantitativa dell'EY apparente, aggiungi massa raccolta e TDS misurato con rifrattometro da caffè.

**Riferimenti**: Jonathan Gagné, *The Physics of Filter Coffee*, 2020, pp. stampate indicate sopra. Ted R. Lingle, *The Coffee Brewing Handbook*, seconda edizione, Specialty Coffee Association of America, 2011. Le scelte numeriche dell'app non sono tabelle o equazioni attribuite a questi autori salvo esplicita indicazione.
