# Itinerario Luglio 2026 🚗🌊

Sito interattivo del nostro viaggio in famiglia da **Como al Sud e ritorno** (11–26 luglio 2026).

Ogni tappa è espandibile e mostra struttura, contatti, costi ripartiti tra "Noi" e "Nonni", e pulsanti per aprire il tragitto su **Google Maps** o chiamare la struttura.

## 🌐 Come pubblicarlo su GitHub Pages

1. Crea un nuovo repository su GitHub (es. `itinerario-2026`), pubblico.
2. Carica il file `index.html` (basta questo: è tutto in un unico file).
3. Vai su **Settings → Pages**.
4. Alla voce *Source* seleziona il branch `main` e la cartella `/ (root)`, poi **Save**.
5. Dopo circa un minuto il sito sarà online all'indirizzo:
   `https://TUO-UTENTE.github.io/itinerario-2026/`

Fatto! Ogni volta che modifichi `index.html` e fai commit, il sito si aggiorna da solo.

## 📝 Modificare i dati

Tutti i dati (tappe, costi, telefoni, indirizzi) sono nell'array `stops` dentro `index.html`, in fondo alla pagina nella sezione `<script>`. Sono facili da modificare anche senza conoscere la programmazione.

## ℹ️ Note
- I telefoni di **Conero** e **Bologna** sono stati recuperati online: conviene verificarli con una chiamata.
- Le quote di **Matera** e **Leuca** sono ripartite in proporzione alle persone (Noi 4/6, Nonni 2/6), da confermare con le strutture.
