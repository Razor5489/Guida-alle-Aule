# Guida alle Aule di Hogwarts

Sito illustrato per orientarsi tra le sette aule della scuola, anno 1890.

## Contenuti
- Trasfigurazione
- Pozioni
- Erbologia
- Cura delle Creature Magiche (aula interna nell'Ala di Astronomia)
- Storia della Magia
- Difesa Contro le Arti Oscure
- Incantesimi

La pagina principale è `index.html`. Include indice, ricerca, filtri per ala, descrizioni dei percorsi a piedi, copia delle istruzioni e impaginazione adattiva per telefono e desktop.

## Pubblicazione
Per rendere il sito pubblico:
1. Aprire **Settings → Pages** nel repository GitHub.
2. In **Build and deployment**, scegliere **Deploy from a branch**.
3. Selezionare **main** e **/(root)**, quindi salvare.
4. Il sito sarà raggiungibile all'indirizzo `https://razor5489.github.io/Guida-alle-Aule/` dopo l'attivazione della pubblicazione.

## Fotografie
Il sito cerca i sette file nell'area `images/`. La procedura GitHub Actions `.github/workflows/importa-fotografie.yml` tenta di scaricare le fotografie del documento originale e salvarle nel repository. Se non riesce, caricare manualmente in `images/` i file:
`trasfigurazione.png`, `pozioni.png`, `erbologia.png`, `creature-magiche.png`, `storia-della-magia.png`, `difesa-arti-oscure.png`, `incantesimi.png`.

La pagina mostra un elemento grafico sostitutivo per eventuali immagini non disponibili.
