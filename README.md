# Cifrari di Cesare e Vigenère

Un laboratorio interattivo di crittografia classica scritto in **Wolfram Mathematica**. Unisce la teoria, strumenti visuali per sperimentare ed esercizi con correzione automatica, per imparare come funzionano e come si attaccano due dei cifrari più antichi della storia.

> Progetto del corso di **Matematica Computazionale**, Laurea Magistrale in Informatica, Università di Bologna (a.a. 2025/2026).
> Valutazione finale: **30 e lode**.

## Cosa contiene

**Il tutorial** (`Laboratorio_Crittografia_Arcaica.nb`) è diviso in capitoli:

1. Introduzione alla crittografia
2. Il Cifrario di Cesare
3. Il Cifrario di Vigenère
4. Approfondimenti
5. Bibliografia
6. Commenti e lavoro futuro

**Il pacchetto** (`CrittografiaArcaica.m`) implementa:

- **Cifratura e decifratura** con Cesare (shift fisso) e Vigenère (chiave ripetuta)
- **Ruota di Cesare interattiva** per vedere lo spostamento lettera per lettera
- **Tabella degli shift di Vigenère**, che mostra come ogni lettera della chiave trasforma il testo
- **Analisi delle frequenze** con grafico, alla base della crittoanalisi di Cesare
- **Esercizi generati automaticamente** a partire da parole italiane del dizionario di Mathematica, riproducibili tramite seed e con verifica immediata della risposta

## Struttura della repository

| File | Descrizione |
| --- | --- |
| `Laboratorio_Crittografia_Arcaica.nb` | Notebook con teoria, esempi interattivi ed esercizi |
| `CrittografiaArcaica.m` | Pacchetto con i cifrari, le interfacce grafiche e il generatore di esercizi |

## Come usarlo

**Requisiti:** Mathematica 14 o superiore e una connessione a Internet, necessaria la prima volta per scaricare il dizionario italiano usato da `DictionaryLookup`.

1. Clona o scarica la repository:
   ```bash
   git clone https://github.com/MatteMito/MC-Project.git
   ```
2. Apri `Laboratorio_Crittografia_Arcaica.nb`, tenendo `CrittografiaArcaica.m` nella stessa cartella.
3. Valuta il notebook dall'inizio: *Valutazione → Valuta notebook*.
4. Nelle sezioni II.3 e III.3 usa i bottoni per aprire gli esercizi.

## Limitazioni

- Si usano solo le lettere `A–Z`: i caratteri accentati non sono supportati.
- Per generare gli esercizi serve il dizionario italiano di Mathematica.

## Autori: gruppo "I Cesaroni"

- Matteo Boscherini
- Alessandro Campedelli
- Francesco Maria Fuligni
- Mattia Furini
- Mohamed Samir Haffoudhi
