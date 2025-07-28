In generale, i comandi da console hanno questa sintassi:
nomeDelComando -o1 -o2 --option3 argomento1 argomento2

Primi comandi:
clear


File System composto da:
- file
- directory

Ogni file e ogni directory è individuata da un path (percorso)


Path:
- path assoluti rispetto alla root del file system (iniziano con /)
- path relativi rispetto ad un altro path (iniziano con .)

Alias per i path:
~ (tilde) path della home dell'utente attualmente loggato nel Sistema Operativo
. "nella directory in cui mi trovo attualmente"
.. la directory parent

Comandi File System - Directory
pwd     print working directory
ls      list
cd pathDellaDirectory     change directory
mkdir nomeDellaDirectory  make directory
cp -r pathDellaDirectorySource pathDellaDirectoryDest    (copy - con le directory è necessario includere l'opzione recursive)
mv pathDellaDirectorySource pathDellaDirectoryDest (move)
rm -r pathDellaDirectory (remove - con le directory è necessario includere l'opzione recursive)


Comandi File System - File
touch nomeDelFile (crea un file vuoto con il nome specificato)
cat pathDelFile (stampare il contenuto del file sulla console)


Nei sistemi operativi unix, l'editor di testo di default si chiama vim

vim nomeDelFile
vim listaDellaSpesa.txt

vim ha due modalità di funzionamento:
- command mode (modalità selezionata all'apertura di vim)
- insert mode

Per passare dalla command mode alla insert mode devo premere il tasto i
Per passare dalla insert mode alla command mode devo premere il tasto esc

I comandi utili sono:
:wq         (write and quit)
:q!         (! significa force)




