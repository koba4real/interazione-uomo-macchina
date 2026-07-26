# BrainBox — Elaborato di Interazione Uomo-Macchina

Elaborato per il corso di **Interazione Uomo-Macchina** (Progetto HCI), Corso di Laurea in
Ingegneria Informatica — Dipartimento di Ingegneria dell'Informazione.

Docente: **Prof.ssa Daniela Fogli** · Anno Accademico 2025/2026

## Il progetto

Studio di usabilità della piattaforma web **BrainBox**, un ambiente digitale integrato a supporto
degli studenti universitari nelle attività di studio. Le funzionalità analizzate comprendono:

- un archivio di materiale didattico, con appunti personali condivisibili con la *community*;
- la trascrizione automatica di lezioni registrate (*Sbobinatore AI*);
- la sintesi vocale di appunti e trascrizioni (*Generatore AudioNote*);
- la pianificazione dello studio in vista degli esami (*StudyFlow*);
- l'interazione sociale tramite commenti ai documenti condivisi.

L'elaborato percorre il ciclo completo di valutazione dell'usabilità: dall'analisi del profilo
utente alla valutazione euristica, dalla riprogettazione dell'interfaccia all'esperimento con
utenti reali, fino all'analisi statistica dei dati raccolti (questionario **SUS**, **t-test** e
correlazione con i risultati della valutazione euristica).

## Struttura

| File | Contenuto |
| --- | --- |
| `main.tex` | documento principale, include tutti i capitoli |
| `01-introduzione.tex` | descrizione del sistema e delle sue sezioni |
| `02-profilo-utente.tex` | analisi del profilo utente |
| `03-valutazione-euristica.tex` | valutazione euristica e frequenza delle violazioni |
| `04-riprogettazione.tex` | analisi dei compiti e riprogettazione dell'interfaccia |
| `05-esperimento-utenti.tex` | progettazione dell'esperimento con utenti |
| `06-analisi-dati.tex` | analisi dei dati, questionario SUS, t-test |
| `07-sviluppi-futuri.tex` | sviluppi futuri e problemi non risolti |

Le cartelle `valutazione-euristica/`, `riprogettazione/`, `esperimento-utenti/` e `analisi-dati/`
contengono i sorgenti dei singoli paragrafi; `figures/` e `Screenshots/` le immagini.

Il PDF compilato è disponibile in [`out/main.pdf`](out/main.pdf).

## Compilazione

Il progetto usa `latexmk` con output nella cartella `out/` (vedi `.latexmkrc`):

```bash
latexmk -pdf main.tex
```

## Autori

- **Okba Kharef** — 728139
- **Matteo Legati** — 735612
- **Simone Rinaldi** — 737270

> La cronologia completa dei commit è stata preservata dal repository originale del gruppo,
> mantenendo l'attribuzione di ogni contributo ai rispettivi autori.
