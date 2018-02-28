# Oppgaveplattform - Blueprint
Denne er laget for plugnplay.
## "Installasjon"
## Som git repo (anbefalt):
Klon dette repoet. Oppgaveplatform er lagt her som en submodul. Dette er for at mappestrukturen skal se finere ut, og at oppdateringer skal være mulige.

Git-clone repoet (inkludert submodul) med 

```git clone --recursive https://github.com/Strauman/OppgaveplattformShell```.

## Som zip fil:
GitHub zip fil vil ikke gi submoduler med i nedlastinger, så https://github.com/Strauman/Oppgaveplattform må legges inn med mappenavn "platform" for at dette skal virke.
Last ned som zip-fil:

1) Last ned [Denne zipfila](https://github.com/Strauman/OppgaveplattformShell/archive/master.zip)
2) Pakk den ut, og last ned [denne zipfila](https://github.com/Strauman/Oppgaveplattform/archive/master.zip)
3) Pakk ut den siste zipfila, og kall mappen `platform`. Legg den inni mappa til den første zipfila.

# Quick start:
Etter installasjonen:

Lag en fil som heter `1.tex` og legg den i`sett/`-mappa. Endre filnavnet til fila `config-sample.tex` og kall den `config.tex`. Sørg for at `\Sets{1}` er i config-fila. Bygg (`main.tex`). And you're golden. Les gjerne [`readme.pdf`](https://github.com/Strauman/Oppgaveplattform/blob/master/readme.pdf).


