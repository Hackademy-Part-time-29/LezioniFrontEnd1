git è un distribuited version control system.


git tiene traccia dei cambiamenti apportati ad un file
oppure ad un insieme di file (interni al progetto) nel tempo.

// sul mac
xcode-select install

// parole chiave
repository insieme di dati (sottoforma di file e directory) utili a git per tener traccia dei cambiamenti apportati ai file del progetto nel tempo
branch
commit


// configurazione di git
git config --global user.name "Giuseppe Calia"
git config --global user.email "giuseppe.calia90@gmail.com"


// comandi
git init (operazione one time - eseguita dall'owner del progetto) -> per inizializzare la repository locale del progetto (verra creato un branch chiamato di default master)


git status -> ispezioniamo il contenuto dell'area di staging
git add . 

git log -> ispezioniamo il contenuto del branch (insieme dei commits)
git commit -m "messaggino descrittivo del commit"



git checkout




// remote
git remote add {alias} {url}
git branch -M main -> rinomina il branch da master a main

git push origin main -> per spingere (verso l'alto) il contenuto del main branch della repository locale all'interno della repository remota
git pull origin main -> per tirar giù il contenuto del main branch della repository remota all'interno della repository locale 

git clone (operazione one time - eseguita dai collaborators del progetto) per clonare il contenuto di una repository remota in una repository locale nuova di zecca
