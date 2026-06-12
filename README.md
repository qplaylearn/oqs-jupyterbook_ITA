[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

# Sistemi quantistici aperti con qiskit

Questa serie di notebook contiene il materiale didattico per un corso completo di 54 ore sui sistemi quantistici aperti (OQS), che parte dai concetti di base e copre gli aspetti fondamentali della letteratura sull'argomento. Inoltre, presentiamo un'idea innovativa: insegnare come simulare molti esempi paradigmatici delle dinamiche degli OQS utilizzando Qiskit e i processori IBM Q. Questa idea trova la sua origine in una recente pubblicazione ([García-Pérez, Rossi, Maniscalco, NPJ Quantum Inform. 6, 1 (2020)](https://www.nature.com/articles/s41534-019-0235-y)), in cui dimostriamo che IBM Q Experience è una piattaforma versatile e robusta per la simulazione di sistemi quantistici aperti.

Il corso è rivolto a studenti di master con una preparazione in meccanica quantistica e teoria dell'informazione quantistica, che abbiano inoltre familiarità con Qiskit. È suddiviso in lezioni frontali e progetti. Attraverso gli appunti delle lezioni, il docente fornirà diversi esempi di concetti fondamentali per l'OQS in termini di circuiti, che si presume lo studente conosca già. Il materiale didattico include anche molti circuiti che consentono la simulazione delle dinamiche OQS sui dispositivi IBM Q reali, con spiegazioni esaurienti sui loro principi di funzionamento. Infine, le lezioni saranno integrate da sessioni pratiche guidate in cui gli studenti dovranno implementare i circuiti corrispondenti e analizzare i risultati.

[Link al sito](https://qplaylearn.github.io/oqs-jupyterbook)

## Installazione
Per poter utilizzare i notebook del corso e riprodurne i risultati, clona il repository sul tuo dispositivo e crea un ambiente Python 3.11.10 utilizzando il metodo che preferisci (virtualenv, conda o poetry). Ad esempio, con poetry

```shell
poetry install
```

Con pip,

```shell
pip install -r requirements.txt
```

## Utilizzo

I notebook  sono collocati nella cartella `content` dentro la repository.

----

Autori: Daria Anttila, Guillermo García-Pérez, Matteo Rossi, Boris Sokolov


Questo lavoro è concessa in licenza ai sensi di [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
