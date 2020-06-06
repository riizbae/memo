# memo commande bash

**ctrl T** raccourcit pour ouvrir bash

## Les commandes de gestion des répertoires et des fichiers 

**pwd** affiche le chemin absolu du répertoire courant

**ls** list, affiche les répertoires et les fichiers du répertoire actif
  * *ls* affiche seulement les noms
  * _ls toto*_ affiche les fichiers commençant par toto
  * *ls -l* affiche le format long : types + droits + Nbre de liens + ....

**cd** change directory
  * *cp chemin* vers le répertoire dont le chemin absolu est donné
  * *cd ..* répertoire parent
  * _cd ~_ répertoire de base
  * *cd -* répertoire précedent
  * *cd /* répertoire racine
  
**cp** copie
  * _cp rapport*.txt_ sauvegarde
  * _cp  * dossier_ copie

**mv** move, renomme et déplace un fichier
  * *mv source destination*
  * _mv * dossier_ déplace tous les fichiers du répertoire actif vers le répertoire
dossier

**mkdir** créer un répertoire
 * *mkdir répertoire*

**rmdir** effacer un répertoire
 * *rmdir dossier* supprime un répertoire vide

**rm** remove, éfface!!!
 * *rm -R* enlèvement récursif!!!
 * *rm fichier*
 * *rm -i fichier* interactivement, avec demande de confirmation
 * *rm -f fichier* avec force, sans demande de confirmation
 * *rm -r fichier* avec récursivité, avec les sous répertoires
 * *rm -rf dossier* supprime le répertoire et tou son contenu, sans confirmation

## Les commandes de recherche

**grep** recherche les occurences de mots à l'intérieur de fichier)
 * *grep motif fichier*
 * *grep -i motif fichier* sans tenir compte de la casse
 * *grep -c motif fichier* en comptant les occurences
 * *grep -v motif fichier*  inverse la recherche, en excluant le "motif"
 * *grep expression /répertoire/fichier*
 * *grep [aFm]in /répertoire/fichier*
 * *grep "\$" *.txt*


## Les commandes d'édition

**more** "pager" qui affiche page par page sans retour en arrière, "h" affiche
l'aide contextuelle
 * _more fichier_
 * _more fichier1 fichier2_
 * _more *.txt_

__cat__ concatenate avec le code de fin de fichier eof=CTRL + D
 * _cat fichier-un fichier-deux > fichier-un-deux_
 * _cat -n fichier > fichier-numéroté_ crée un fichier dont les lignes sont
numérotés
 * _cat -nb fichier_ affiche sur la sortie standard les lignes numéroté, sauf les
lignes vides

**head** affiche les 10 premières lignes d'un fichier
 * * _head -n22 fichier_* affiche les 22 premières lignes


