git è un    distribuited     version control system


git config --global user.name "Eric Cartman"
git config --global user.email "eric.cartman@gmail.com"



repository è una struttura dati riguardandi la history del progetto sottoforma di file e directory
branch è una linea di sviluppo nel tempo
commit una istantanea del progetto


per inizializzare una repository locale vuota:
git init


Working directory è la cartella del progetto


Staging area: anteprima di stampa
git add pathDelFile
git add .

Per visualizzare lo stato della staging area:
git status


A partire dai file presenti nella staging area posso creare un commit
git commit -m "una descrizione"


Possiamo visualizzare la sequenza dei commit (la history del progetto):
git log

in modo più rapido
git log --oneline





GitHub è un servizio di hosting per repository git

le chiavi ssh sono una coppia di chiavi pubblica e privata utile per autenticarci su GitHub



rinomino il branch di default da master a main
git branch -M main





il comando git remote crea una alias (in questo caso origin) per l'url della repository
git remote add origin URL

il comando git push esegue un upload dei commit presenti nel branch main della repository locale verso il corrispondente branch main della repository remota 
git push origin main

upstream branch
git push -u origin main

il comando git pull esegue un download dei commit presenti nel branch main della repository remota verso il corrispondente branch main della repository locale 
git pull origin main

Il comando git clone URL copia il progetto e tutto il contenuto della repository remota per creare una nuova repository locale

I comandi git init e git clone sono operazioni one time



Risoluzione del conflitto:
- saranno presenti dei delimitatori (sono testo!!!!)
- un conflitto terminare con un "commit di risoluzione del conflitto"





