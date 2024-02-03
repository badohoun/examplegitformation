# Exemple de Git Repository

On apprend comment faire des commits .

1. Effectuer des changements 
2. git add -- "stage" les changements qu'on aimeraient voir persister avec les différents historiques git 
3. git commit -m "message qui correspond aux changements qui ont été apportés aux fichiers en terme d'ajout de ligne ou de suppression de lignes"








command + control + shift + 4 (mac)
Windows shift s  (windows)

repositories , branches , commits , tags

```
# creation de repo en local 
local_repository -> "remote" repository ( git add remote <name> <URL>)

# creation de repo en remote 
git clone  <URL>

# creation de la branch en local 
git checkout <branch>
git checkout -b <nouvelle branche>
git add ...; git commit -m "...." ( le faire souvent , régulièrement , avec des messages clairs correspondants aux modifications apportées)
git push --set-upstream origin <nouvelle branche>
git pull [origin <nouvelle branche>]

# creation d'une nouvelle branche en remote 

utilisant l'Ui de github pour créer <branche>
git checkout -b <branch>; git pull origin <branch> 

git fetch --all 
git checkout <branch> 




Comment contribuez-vous au code d’un logiciel open source ?


    * quel est le flux de travail pour ce processus ?
Comment vous assurer que le code contribué est « propre » ou « bon »

    * Réponse:  code review 
C'est quoi la notion de "clean code"? ou code propre 

   1. Scan automatique de la qualite du code 
   **. Continuous integration  
Comment publier mon logiciel?
Python packaging ( comment faire un  package python de la bonne manière) /
               Continuous Delivery 

    bon travail 