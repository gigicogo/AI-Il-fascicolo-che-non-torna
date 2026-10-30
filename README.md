# 🔍 Il fascicolo che non torna

**Il fascicolo che non torna** è un laboratorio individuale per esercitare il controllo qualità e la validazione delle risposte generate dall’IA nella Pubblica Amministrazione.

Il partecipante riceve una relazione trimestrale sulle manutenzioni degli edifici pubblici, generata da un’IA **simulata**. Il testo è scorrevole e dall’aspetto istituzionale, ma contiene affermazioni corrette, errori e un dato non dimostrabile: sarà il partecipante a scoprirlo confrontando la bozza con le fonti originali.

## 🎯 A chi è rivolto

L’esercitazione è pensata per:

- funzionari ed esecutori della Pubblica Amministrazione;
- responsabili di uffici tecnici, servizi e procedure amministrative;
- direttori e dirigenti coinvolti nella validazione dei documenti;
- referenti ICT, qualità, controllo interno e trasformazione digitale;
- formatori che vogliono proporre un laboratorio pratico sulla verifica degli output IA.

## 🧠 L’obiettivo

L’esercitazione mostra che la fluidità di un testo e l’approvazione di un secondo modello AI non sono sufficienti a considerarlo affidabile.

Il partecipante impara a:

- distinguere fatti documentati, affermazioni errate e informazioni non dimostrabili;
- costruire una checklist di controllo basata su dati, scadenze, soggetti ed eccezioni;
- risalire alle fonti originali prima di accettare una conclusione;
- riconoscere i limiti di un secondo parere AI;
- correggere, mantenere o sospendere le affermazioni;
- lasciare traccia delle verifiche effettuate.

## 🕹️ Come funziona

La durata indicativa è di **25–30 minuti**, con 3–5 minuti finali facoltativi di discussione.

Il percorso è diviso in sei fasi obbligatorie:

| Fase | Attività |
|---:|---|
| 1. **Valuta la bozza** | Scegli il metodo di controllo e le priorità da adottare. |
| 2. **VER-01** | Seleziona le affermazioni che richiedono un riscontro fattuale o documentale. |
| 3. **Apri le fonti** | Classifica sette affermazioni e individua la fonte pertinente. |
| 4. **Secondo parere** | Valuta i limiti di una risposta concordante di un’altra IA. |
| 5. **Correggi** | Decidi se mantenere, correggere o sospendere ogni affermazione. |
| 6. **Traccia** | Compila la registrazione delle verifiche, scarica o stampa il riepilogo. |

Per avanzare è necessario completare correttamente ciascuna fase. In caso di errore, l’app fornisce indicazioni per riprovare.

## 📚 Il caso didattico

La simulazione mette a disposizione tre documenti fittizi:

| Documento | Contenuto |
|---|---|
| **A — Procedura interna per le manutenzioni** | Regole su segnalazioni ordinarie, urgenze e chiusura degli interventi. |
| **B — Report trimestrale sulle segnalazioni** | Dati su segnalazioni ricevute, prese in carico, chiuse e tempi di presa in carico. |
| **C — Nota operativa sulle eccezioni** | Informazioni sulle urgenze e limiti dei confronti tra categorie di segnalazioni. |

La bozza IA contiene sette affermazioni da verificare, tra cui:

- il numero totale delle segnalazioni ricevute;
- la percentuale delle segnalazioni risolte;
- il termine di tre giorni lavorativi;
- la situazione delle segnalazioni urgenti;
- un dato sul tempo medio di chiusura non presente nelle fonti;
- l’esistenza o meno di eccezioni procedurali.

## ✅ Esito finale

Al termine del percorso, la relazione assume lo stato di:

> **Bozza revisionata da sottoporre a validazione.**

Non è un provvedimento, non viene firmata e non è approvata automaticamente. La validazione organizzativa e la responsabilità della persona competente restano sempre distinte.

## 🧪 Valutazione

Il punteggio conserva le risposte corrette date **al primo tentativo**.

- Il punteggio è un feedback formativo.
- Non blocca il completamento dell’esercitazione.
- Non costituisce una certificazione di competenze.
- Serve a rivedere le scelte e a comprendere meglio il metodo di verifica.

## 💻 Come usare l’app

L’app è una **web app statica autonoma**, contenuta in un unico file `index.html`.

- Non richiede account, registrazione o installazione.
- Non utilizza API, IA esterne o servizi online.
- Funziona offline, anche con doppio clic sul file.
- È compatibile con Chrome, Edge, Firefox e Safari aggiornati.
- Funziona anche da smartphone, ma il confronto con le fonti è più comodo su computer.

### Aprire l’esercitazione

1. Scarica o clona il repository.
2. Apri `index.html` con un browser moderno.
3. Avvia la revisione e completa le sei fasi.

### Clonare il repository

```bash
git clone [https://github.com/gigicogo/AI-Il-fascicolo-che-non-torna.git](https://github.com/gigicogo/AI-Il-fascicolo-che-non-torna.git)
cd AI-Il-fascicolo-che-non-torna
```

## 🔐 Privacy e dati

La pagina:

- non invia richieste di rete;
- non usa analytics, iframe, CDN, cookie o link remoti obbligatori;
- conserva le risposte solo nella memoria temporanea del browser;
- cancella le risposte al ricaricamento della pagina;
- utilizza documenti, cifre e output IA interamente inventati.

L’esportazione del riepilogo in `.txt`, la stampa o il salvataggio in PDF sono azioni locali del partecipante.

Non incollare informazioni personali, pratiche reali o documenti riservati nel campo delle osservazioni.

## 📝 Nota didattica

Le regole richiamate dalle slide — **CoVe**, **VER-01**, **VER-02**, verifica incrociata e tracciabilità — sono applicate in forma semplificata.

L’app non simula un vero sistema di IA con capacità di ragionamento o accesso a fonti esterne: le risposte simulate sono predefinite e dichiarate. La verifica sulle fonti originali, la responsabilità della persona competente e la validazione organizzativa restano elementi separati.

## 🛠️ Personalizzazione

Tutto il contenuto è contenuto nel file `index.html`.

Gli oggetti JavaScript principali sono:

| Oggetto | Contenuto |
|---|---|
| `DOCS` | Fonti fittizie del fascicolo. |
| `CLAIMS` | Affermazioni della bozza IA da verificare. |
| `TRIAGE` | Domande iniziali sul metodo di controllo. |
| `CHECKLIST` | Voci della checklist VER-01. |
| `CROSS` | Domande sul secondo parere AI. |

Puoi adattare testi, numeri e casi, mantenendo la coerenza tra affermazioni, fonti, esiti corretti ed evidenze.

## 🧪 Possibili evoluzioni

- Aggiunta di nuovi fascicoli e settori amministrativi.
- Modalità per gruppi, con confronto delle revisioni.
- Esportazione del riepilogo in Markdown o PDF strutturato.
- Versione inglese dell’esercitazione.
- Integrazione con checklist organizzative e procedure di validazione.
- Nuovi scenari su budget, contratti, bandi, comunicazioni e reportistica.

## 🤝 Contribuire

Sono benvenuti suggerimenti su nuovi casi, miglioramenti didattici, correzioni e materiali di supporto.

1. Apri una Issue per proporre un’idea o segnalare un problema.
2. Oppure apri una Pull Request con una modifica o un nuovo scenario.
3. Mantieni la coerenza tra fonti, affermazioni, esiti e verifiche richieste.

---

## 📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file `LICENSE` del repo.

## 👤 Autore e contesto

**Gianluigi Cogo**  
Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell’IA generativa nella Pubblica Amministrazione.

L’app nasce come esercitazione nel percorso operativo **“L’IA nella Pubblica Amministrazione — Percorso operativo per l’uso consapevole, sicuro e governato dell’IA generativa”** (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattami usando i social qui sotto.

- 📮 **Newsletter:** [gigicogo.substack.com](https://gigicogo.substack.com)
- 📝 **Blog:** [medium.com/webeconoscenza](https://medium.com/webeconoscenza)
- ▶️ **YouTube:** [youtube.com/@gigicogo](https://youtube.com/@gigicogo)
- 💼 **LinkedIn:** [linkedin.com/in/gigicogo](https://www.linkedin.com/in/gigicogo)
