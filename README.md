# My English Coach — versione iniziale

Questa è una prima versione dimostrativa di una Progressive Web App (PWA) per imparare l'inglese.
È realizzata con HTML, CSS e JavaScript senza librerie esterne e senza API a pagamento.

## Funzioni incluse
- Interfaccia responsive in italiano.
- Lezioni dimostrative A1 con spiegazioni ed esempi.
- Esercizi di completamento, scelta multipla e riordino parole.
- Correzione immediata e registro degli errori.
- Punti, progressi e serie di giorni di studio.
- Vocabolario personale.
- Appunti personali.
- Esportazione/importazione del backup JSON.
- Manifest e service worker per installazione PWA e cache di base.

## Limiti attuali
- Contiene solo lezioni dimostrative, non l'intero corso A1-A2.
- Non contiene ancora audio, riconoscimento vocale o conversazione AI.
- I dati sono salvati nel localStorage del browser: non esiste sincronizzazione/account.
- La cache offline va collaudata dopo la pubblicazione HTTPS.
- Non è ancora stata collaudata su tutti i browser/dispositivi.

## Pubblicazione gratuita
Può essere pubblicata su un hosting statico gratuito che supporti HTTPS, ad esempio GitHub Pages, verificando le condizioni correnti del servizio. Per pubblicarla sarà necessario creare/configurare un repository e caricare questi file. Il repository GitHub Pages gratuito è normalmente pubblico: non inserire dati personali o segreti nel codice.

## File
- `index.html`: interfaccia e logica principale.
- `manifest.webmanifest`: metadati PWA.
- `service-worker.js`: cache di base per uso offline limitato.
- `icons/icon.svg`: icona.
