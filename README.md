# CreatorFlow AI · Download per Windows

Studio desktop per creare immagini e video di marketing dai propri prodotti, con modelli creativi riutilizzabili, Nano Banana e HeyGen. Prima genera e controlla tre foto, poi passa al video.

**[Scarica CreatorFlow AI per Windows](https://github.com/IlSamm/CreatorFlow-AI-Updates/releases/latest/download/CreatorFlow-AI-Setup.exe)**

[Note dell’ultima versione](https://github.com/IlSamm/CreatorFlow-AI-Updates/releases/latest)

## Installazione e aggiornamenti

1. Chiudi la versione precedente e avvia `CreatorFlow-AI-Setup.exe`.
2. Usa il collegamento **CreatorFlow AI** creato dall’installazione.
3. Dalla 1.8.0 apri **Aggiornamenti** nella barra laterale, scarica e scegli **Riavvia e aggiorna** quando le produzioni sono terminate. Nelle versioni precedenti la voce si trova in **Impostazioni → Aggiornamenti**.

Progetti, modelli e impostazioni rimangono nelle cartelle del tuo profilo Windows. Il link di download conserva sempre lo stesso nome; non occorre gestire più copie portatili. Le versioni precedenti alla 1.6 richiedono questa prima installazione.

## Correzione Gemini HTTP 404 · 1.8.2

Aggiornato il modello predefinito per analisi, prompt e controllo qualità a `gemini-3.5-flash-lite`. Google limita l’accesso alla serie 2.5 per i nuovi utilizzatori. Il vecchio valore predefinito viene migrato una volta; gli altri ID personalizzati restano invariati. Nano Banana usa `gemini-3.1-flash-image`.

In **Impostazioni → Google Gemini**, **Verifica modelli** consulta il catalogo Google con la tua chiave senza generare contenuti. **Usa modelli consigliati** ripristina gli ID correnti: premi **Salva impostazioni** per applicarli. La presenza nel catalogo non conferma quota o fatturazione.

Dopo l’aggiornamento apri il progetto già importato e premi **Riprova**: prodotto, foto originali e testi restano salvati. Gli errori 404 ora indicano esattamente il modello coinvolto.

## Foto reali e recupero TikTok · 1.8.1

Nello Studio la scelta **Importazione senza AI / Generazione AI reale** è esplicita. **Solo foto** seleziona il formato; le anteprime Demo non sono foto generate e non mostrano punteggi di qualità simulati.

Per un progetto Solo foto già importato in Demo, apri **Prodotto → Completa o aggiorna la scheda**. Se TikTok si vede solo sul telefono, trasferisci sul PC le foto originali, selezionale con **Aggiungi foto dal PC** e incolla la descrizione originale. Salvare i dati non avvia generazioni. Poi premi **Genera 3 foto reali**: conserva i tre testi già salvati, verifica i requisiti e avvia Gemini. Se la coda è in pausa, riprendila.

La sessione TikTok del telefono è separata da quella del browser desktop. Il login non garantisce che TikTok renda accessibile la scheda Shop. Se una nuova lettura fallisce, i dati già importati rimangono salvati.

## Provare le sole foto

1. In **Impostazioni**, salva la chiave Gemini.
2. Nello **Studio** scegli **Generazione AI reale** e **Solo foto**.
3. Compila le tre schede in **Modifica modello** e salva. Se i testi sono già presenti, non serve riscriverli.
4. Inserisci il link, premi **Genera 3 foto** e riprendi la coda se è in pausa. I risultati sono nel progetto → **Foto** e in **Apri cartella**.

Non servono chiave HeyGen, script video, ID avatar HeyGen o voce. La generazione usa credito Gemini. Se un progetto Live si ferma per descrizione mancante, completala nella scheda e premi **Riprova**. Tutte le foto recuperate o aggiunte vengono incluse nei riferimenti del prodotto: massimo 60 foto e 120 MB complessivi; per l’importazione manuale, JPG, PNG o WebP fino a 12 MB ciascuna.

## Negozi riconosciuti dalla 1.7

La coda accetta link di TikTok Shop, Amazon, Shopify, AliExpress, Temu e SHEIN. I lettori recuperano titolo, descrizione e foto pubblicamente disponibili, segnalando i dati mancanti. Amazon e Shopify hanno superato una prova reale con descrizione e più foto. AliExpress ha restituito foto ma non la descrizione nel prodotto provato. AliExpress, Temu e SHEIN restano sperimentali; le prove pubbliche di Temu e SHEIN sono state bloccate dal sito.

Non è garantita l’importazione di ogni prodotto. Il collegamento dell’account dentro l’app è specifico di TikTok e può richiedere una verifica personale. L’app non aggira CAPTCHA. In modalità demo importa dati reali senza generazioni AI a pagamento; le fasi creative successive sono simulate.

Windows x64. La build attuale non è firmata con un certificato commerciale. I checksum degli artefatti sono allegati alle release. Le generazioni AI richiedono account, accessi e credito sui rispettivi servizi; il collaudo Live completo con gli account di destinazione deve ancora essere eseguito.

Questo repository ospita gli aggiornamenti pubblici. Il repository sorgente è privato.
