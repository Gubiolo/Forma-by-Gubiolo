# Forma by Gubiolo

Web app di design per iPad (Apple Pencil, gesti, Magic Trackpad), in stile iPadOS 26.

## Pubblicare con GitHub Pages

1. Su github.com crea un nuovo repository, per esempio `forma`. Per GitHub Pages gratuito deve essere **Public**.
2. Nel repository: **Add file → Upload files**, trascina tutti i file di questa cartella (non la cartella stessa) e premi **Commit changes**.
3. Vai in **Settings → Pages**. In *Build and deployment* scegli **Deploy from a branch**, branch **main**, cartella **/ (root)**, poi **Save**.
4. Dopo uno o due minuti l'app è online su `https://TUO-UTENTE.github.io/forma/`.

## Installarla sull'iPad

1. Apri l'indirizzo in **Safari**.
2. Tocca **Condividi → Aggiungi alla schermata Home**.
3. Si apre a schermo intero con l'icona gialla.

## Aggiornare l'app

Carica il nuovo `index.html` con **Add file → Upload files**: sostituisce il vecchio. Safari può tenere in memoria la versione precedente per qualche minuto.

## Dove sono i dati

I progetti restano salvati solo sull'iPad, nel browser (non su GitHub). Questa versione ha un archivio separato da quella su Claude: per spostare un progetto usa **Esporta → Copia del progetto (.json)** dalla vecchia e **Importa** nella nuova. Ogni tanto fai una copia .json come backup.

## File

- `index.html` – tutta l'app
- `manifest.webmanifest` – nome, colori e icone per l'installazione
- `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-1024.png` – icone
