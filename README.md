# Scheda del dispositivo

Pagina web a file singolo che mostra in tempo reale le informazioni che il browser può leggere sul dispositivo: sistema operativo (Android, iOS, Windows, macOS), batteria, schermo (risoluzione, densità, gamma colori, HDR, frequenza di aggiornamento misurata), processore, memoria, GPU, rete, archiviazione, codec e sensori.

## Uso

Apri `index.html` in un browser, oppure pubblica il repository con GitHub Pages (vedi sotto).

## Limiti

Un browser non può leggere la capacità della batteria in mAh, la salute della batteria, il modello esatto della CPU o le temperature. Per questi dati serve un’app nativa. La Battery Status API non è disponibile su Safari e Firefox.

## Pubblicazione con GitHub Pages

Il workflow in `.github/workflows/pages.yml` pubblica la pagina a ogni push su `main`. Nelle impostazioni del repository, in **Settings > Pages**, imposta **Source** su **GitHub Actions**.

## Licenza

MIT
