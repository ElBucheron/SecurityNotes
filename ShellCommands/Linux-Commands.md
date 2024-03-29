# Shell Commands

## ./FICHIER

Exécute un programme.

## pwd

Affiche le nom du repertoire courant.

## mkdir NOM

Cree un repertoire.

## ln [ ] CHEMIN

Cree un lien vers un fichier.

```
[-s] cree un lien symbolique
```

## cat FICHIERS

Concatene les contenu de fichiers.

## cat /dev/clip

Affiche le contenu du clipboard

## cat file.txt > /dev/clip

Envoie le contenu de file.txt dans le clipboard

## chmod [ ] FICHIER

Modifie les droits d'acces aux fichiers.

```
[-go]   chmod go-rwx fichier.txt
```

## more FICHIER

Affiche un fichier par ecran.

## tcsh

Shell systeme tcsh.

## bash

Shell systeme bash.

## ps [ ]

Affiche les processus en cours.

```
[-aux] voir tous les prcessus
```

## fg

Place un processus en premier plan.

## bg

Place un processus en arriere plan.

## jobs [ ]

Liste les jobs en cours.

## kill [ ] PID

Envoie un signal a un processus.

```
[-9]    kill -9 5332
```

## nice [ ]

Change la priorite d'un processus.

```
[-10]   nice -10 sleep 30
```

## sleep

Effectue une attente.

```
sleep 10
```

## cut [ ]

Selectionne un champ.

```
cut -d ":" -f 1 FICHIER
```

## grep

Selectionne les lignes voulues.

```
grep toto FICHIER
```

## who

Donne info sur les utilisateur logues.

## whoami

Donne le login de la personne connecte.

## sed [ ]

Editeur de flux.

```
cat test | sed -e 's/t.*//'
```

## emacs               

Editeur evolue de texte.

## file

Fonctions et type de fichiers.

```
file /etc/*
```

## diff FILE1 FILE2

Comparaison de fichier.

## xterm

Ouvre une console en mode graphique.

## mail

Envoi et reception d'email.

## mailq

Affiche la file d'attente de mail.

## lpr [ ]

Impression de fichier.

```
lpr -P fichier.txt
```

## lpq

Affiche la file d'attente d'impression.

## ftp

Ouvre une connexion ftp.

```
ftp -n -v <<**
```

## pstree [ ]

Affiche l'arbre de tous les processus tournant.

## ps -f -u USER

Affiche tous mes processus.

## Ctrl+C

Stop le processus en avant plan.

## Ctrl+Z

Met le processus en avant plan en pause.

## >

Redirection vers un fichier avec creation.
                           cat > fichier.txt

## >>

Redirection vers un fichier par ajout.

```
cat >> fichier.txt
```

## <

Redirection depuis un fichier.

```
cat < fichier.txt
```

Le pipe redirige sorite du 1 vers entree du 2.

```
ls -l | grep t*
```

## \#!

Indique le Shell au debut d'un script.

```
\#!/bin/bash
```

## &

Lance un processus en tache de fond.

```
mozilla &
```

## $*

Retourne la liste des arguments de la commande, dans un script.

## for

Realise une action en boucle.

```
for fich 'ls';do echo $fich;done
```

## if...then...else

Teste si une condition est vraie

## ...fi

```
if [-d toto]
```

## m1101/tp?

Toutes les entrees du rep cammancant par tp.
