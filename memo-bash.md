# memo commande bash

**ctrl T** raccourcit pour ouvrir bash

## Les commandes de gestion des répertoires et des fichiers 

**pwd** affiche le chemin absolu du répertoire courant

**ls** list, affiche les répertoires et les fichiers du répertoire actif
  * **ls** affiche seulement les noms
  * __ls toto*__ affiche les fichiers commençant par toto
  * **ls -l** affiche le format long : types + droits + Nbre de liens + ....

**cd** change directory
  * **cp chemin** vers le répertoire dont le chemin absolu est donné
  * **cd ..** répertoire parent
  * __cd ~__ répertoire de base
  * **cd -** répertoire précedent
  * **cd /** répertoire racine
  
**cp** copie
  * __cp rapport*.txt__ sauvegarde
  * __cp  * dossier__ copie

**mv** move, renomme et déplace un fichier
  * **mv source destination**
  * __mv * dossier__ déplace tous les fichiers du répertoire actif vers le répertoire
dossier

**mkdir** créer un répertoire
 * **mkdir répertoire**

**rmdir** effacer un répertoire
 * **rmdir dossier** supprime un répertoire vide

**rm** remove, éfface!!!
 * **rm -R** enlèvement récursif!!!
 * **rm fichier**
 * **rm -i fichier** interactivement, avec demande de confirmation
 * **rm -f fichier** avec force, sans demande de confirmation
 * **rm -r fichier** avec récursivité, avec les sous répertoires
 * **rm -rf dossier** supprime le répertoire et tou son contenu, sans confirmation