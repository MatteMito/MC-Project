# Caesar and Vigenère Ciphers

An interactive lab on classical cryptography, written in **Wolfram Mathematica**. It combines theory, visual tools to experiment with, and auto-graded exercises, to learn how two of the oldest ciphers in history work and how they can be broken.

> Project for the **Computational Mathematics** course, MSc in Computer Science, University of Bologna (academic year 2025/2026).
> Final grade: **30 cum laude**.

## What's inside

**The tutorial** (`Laboratorio_Crittografia_Arcaica.nb`) is split into chapters:

1. Introduction to cryptography
2. The Caesar cipher
3. The Vigenère cipher
4. Further topics
5. Bibliography
6. Comments and future work

**The package** (`CrittografiaArcaica.m`) implements:

- **Encryption and decryption** with Caesar (fixed shift) and Vigenère (repeated key)
- **Interactive Caesar wheel** to see the shift letter by letter
- **Vigenère shift table**, showing how each key letter transforms the text
- **Frequency analysis** with a chart, the basis of Caesar cryptanalysis
- **Automatically generated exercises** based on Italian words from Mathematica's dictionary, reproducible through a seed and with instant answer checking

## Repository structure

| File | Description |
| --- | --- |
| `Laboratorio_Crittografia_Arcaica.nb` | Notebook with theory, interactive examples and exercises |
| `CrittografiaArcaica.m` | Package with the ciphers, the graphical interfaces and the exercise generator |

## How to use it

**Requirements:** Mathematica 14 or later and an internet connection, needed the first time to download the Italian dictionary used by `DictionaryLookup`.

1. Clone or download the repository:
```bash
   git clone https://github.com/MatteMito/MC-Project.git
```
2. Open `Laboratorio_Crittografia_Arcaica.nb`, keeping `CrittografiaArcaica.m` in the same folder.
3. Evaluate the notebook from the top: *Evaluation → Evaluate Notebook*.
4. In sections II.3 and III.3, use the buttons to open the exercises.

## Limitations

- Only the letters `A–Z` are used: accented characters are not supported.
- Generating exercises requires Mathematica's Italian dictionary.

## Authors: team "I Cesaroni"

- Matteo Boscherini
- Alessandro Campedelli
- Francesco Maria Fuligni
- Mattia Furini
- Mohamed Samir Haffoudhi
