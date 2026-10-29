# Il fascicolo che non torna

Web app didattica autonoma per l'esercitazione individuale **Controllo qualità e validazione delle risposte IA nella Pubblica Amministrazione**, progettata per **25–30 minuti**.

## Che cosa fa

Mette il partecipante nei panni di chi deve verificare una relazione trimestrale sulle manutenzioni degli edifici pubblici, generata da un'IA **simulata**. La relazione contiene affermazioni corrette, errori e un dato non dimostrabile. Tre fonti interamente fittizie sono disponibili nell'app: procedura interna, report trimestrale, nota sulle eccezioni.

Sei passaggi vincolati:

1. **Valuta la bozza:** scegli il metodo e le priorità del controllo.
2. **VER-01:** seleziona le affermazioni che richiedono un riscontro.
3. **Apri le fonti:** classifica sette affermazioni e individua la fonte pertinente.
4. **Secondo parere:** riconosci i limiti di una risposta concordante di un'altra IA.
5. **Correggi:** mantieni, correggi o sospendi ogni affermazione.
6. **Traccia:** compila una breve registrazione delle verifiche; scarica o stampa il riepilogo.

Per avanzare occorre completare correttamente ciascuna fase; in caso di errore compaiono indicazioni per riprovare. Il punteggio conserva le risposte corrette **al primo tentativo**, ma non blocca il completamento del corso.

**Stato finale:** *bozza revisionata da sottoporre a validazione*. Non è un provvedimento, non viene firmato, non è approvato automaticamente.

## Come usarla

- Apri `index.html` con Chrome, Edge, Firefox o Safari aggiornato.
- Non servono account, registrazioni, API, IA esterne o installazione.
- Funziona offline anche con doppio clic sul file.
- Da smartphone funziona, ma il lavoro sulle fonti è più agevole su computer.
- Consiglio: predisporre 30 minuti, con 3–5 minuti finali di discussione facoltativa.

## Privacy e dati

- La pagina **non invia richieste di rete**, non ha analytics, iframe, CDN, cookie o link remoti obbligatori.
- Le risposte rimangono nella memoria temporanea del browser. **Ricaricare la pagina le cancella**.
- Esportare il riepilogo `.txt` o stamparlo/salvarlo in PDF è un'azione locale del partecipante.
- I documenti e i dati presentati sono **inventati** per la simulazione.
- Non incollare informazioni personali o documenti reali nel campo delle osservazioni.

## Nota didattica

Le regole richiamate dalle slide — CoVe, VER-01, VER-02, verifica incrociata e tracciabilità — vengono **applicate in modo semplificato**, senza simulare un vero sistema di IA con capacità di ragionamento o di accesso a fonti esterne. Le risposte simulate sono predefinite e dichiarate. La verifica sulle fonti originali, la responsabilità della persona competente e la validazione organizzativa restano distinte.

## Personalizzazione

Tutto è in un singolo file `index.html`. Gli oggetti JavaScript `DOCS`, `CLAIMS`, `TRIAGE`, `CHECKLIST` e `CROSS` contengono rispettivamente fonti, affermazioni, domande, checklist e secondo parere. Puoi adattare testi e numeri, **facendo attenzione a mantenere coerenti** gli esiti e le evidenze corrette.

📄 Licenza

Da definire: si suggerisce una licenza aperta (es. MIT o CC BY 4.0) per favorire il riuso da parte di altri formatori o altri enti. Sostituisci questo paragrafo con il testo della licenza scelta e il file LICENSE del repo.

👤 Autore e contesto

Gianluigi Cogo Content creator e technical writer interessato ad AI generativa, automazioni, viaggi e strumenti digitali. Consulente e docente sui temi dell'IA generativa nella Pubblica Amministrazione.

L'app nasce come esercitazione nel percorso operativo "L'IA nella Pubblica Amministrazione — Percorso operativo per l'uso consapevole, sicuro e governato dell'IA generativa" (20 ore: percorso base per funzionari ed esecutori + modulo governance per direttori e dirigenti). Per info sul corso contattatemi usando i social qui sotto.

📮 Newsletter: gigicogo.substack.com
📝 Blog: medium.com/webeconoscenza
▶️ YouTube: youtube.com/@gigicogo
💼 LinkedIn: linkedin.com/in/gigicogo
