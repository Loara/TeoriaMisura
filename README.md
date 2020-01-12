# TeoriaMisura
Questo progetto nasce dal voler fornire a tutti gli studenti di Matematica e non, purché interessati, delle dispense libere e gratuite sulla teoria geometrica della misura.

Chiunque è invitato a contribuire alla stesura degli appunti, sia completando le sezioni vuote già presenti sia proponendo nuovi argomenti inerenti alla teoria geometrica della misura utili all'apprendimento. Si ricordi di fornire, insieme al proprio contributo, anche le opportune referenze bibliografiche che dovranno poi essere aggiunte al documento finale.

Il documento sarà scritto interamente in LaTeX mentre la bibliografia sarà generata con Biblatex/Biber. Inoltre presenterà un indice analitico (generato con il pacchetto `imakeidx`) e una lista dei simboli (generato con i pacchetti `glossaries` e `glossaries-extra`).

# Compilazione
Una volta scaricato il repository per generare il PDF bisognerà digitare da terminale il comando

```
pdflatex main.tex
```

Per generare anche la bibliografia si dovranno eseguire anche i seguenti comandi

```
biber main
pdflatex main.tex
```
