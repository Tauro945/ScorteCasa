# Scorte di casa (PWA)

## Pubblicare su GitHub Pages
1. Crea un repository su GitHub (es. `scorte-casa`), anche privato se hai un piano che permette Pages privato; altrimenti pubblico.
2. Carica **tutti** i file di questa cartella nella root del repo (comprese `icons/` e `.nojekyll`).
3. Settings → Pages → Source: "Deploy from a branch" → branch `main`, cartella `/ (root)` → Save.
4. Dopo 1-2 minuti l'app è su `https://TUO-UTENTE.github.io/scorte-casa/`.

## Installare su iPhone
1. Apri l'URL **con Safari**.
2. Tasto Condividi → "Aggiungi alla schermata Home" → Aggiungi.
3. Apri l'app dall'icona Home.

## Importante: i dati
- I dati sono in localStorage: sono **separati** tra Safari e l'app installata, e tra un dispositivo e l'altro.
- Prima di installare, da dove usi ora l'app: Prodotti → Genera backup. Poi nell'app installata: Ripristina da file.
- Fai backup periodici: se elimini l'app dalla Home, i dati vanno persi.

## Aggiornare l'app
Nel repo sostituisci solo `index.html` (rinomina il nuovo file in `index.html` prima di caricarlo).
Non serve toccare altro. Apri l'app con internet: scarica la nuova versione e la usa subito (o al riavvio successivo).
