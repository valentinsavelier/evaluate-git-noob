# Évaluation Git pour les débutants

Code source pour tester vos connaissances Git avec un niveau débutant.

## Pré-requis

Git doit être installé.

Un navigateur web "moderne" doit être installé.

### Installation

Vous devez "forker" ce dépôt sur votre compte GitHub personnel.

Un nouveau dépôt distant sera alors disponible :

https://github.com/VOTRE-IDENTIFIANT-GITHUB/evaluate-git-noob

Vous devez cloner VOTRE dépôt distant en local sur votre ordinateur.

```sh
git clone https://github.com/VOTRE-IDENTIFIANT-GITHUB/evaluate-git-noob
```

Une fois le clonage réalisé, n'oubliez pas de vous positionner dans le répertoire créé.

```sh
cd evaluate-git-noob
```

## Exercices

Attention à la fin de l'évaluation, même si vous n'avez pas terminé tous les exercices, VOUS DEVEZ ABSOLUMENT pousser votre branche master (qui doit contenir vos commits) sur VOTRE dépôt distant.

```sh
git push origin master
```

Vous devez également pousser vos tags (si vous en avez créé) sur VOTRE dépôt distant.

```sh
git push origin lenomdutag
```

### Exercice 1

Dans le fichier reponses.txt, merci d'indiquer le SHA1 du commit (uniquement les 7 premiers caractères) appartenant à la branche master qui a pour message "Initial commit".

Faites un commit pour cette modification du fichier ayant le message "Solution exercice 1".

### Exercice 2

Dans le fichier reponses.txt, merci d'indiquer le SHA1 du commit (uniquement les 7 premiers caractères) appartenant à la branche emojiAmour qui a pour message "Ajout des coeurs".

Faites un commit pour cette modification du fichier ayant le message "Solution exercice 2".

### Exercice 3

Vous devez fusionner la branche emojiAmour à la branche master afin de récupérer sur la branche master le nouvel emoji.

### Exercice 4

Positionnez vous sur la branche emojiClinDOeil pour visualiser ce qu'elle apporte.
Sans modifier cette branche, vous devez ensuite la fusionner à la branche master.

### Exercice 5

À partir de la branche master, vous devez créer une nouvelle branche qui doit s'appeler "emojiSurprise". Sur cette branche vous pouvez laissez libre cours à votre imagination pour créer votre propre emoji en transformant la matrice de caractères de la variable emojiSurprise. Par contre vous devez le faire en 2 commits, le premier concernera les yeux et le deuxième concernera la bouche.
Vous devez également ajouter un tag sur le premier commit qui aura pour label "surprise1" et un tag sur le deuxième commit qui aura pour label "surprise2".

### Exercice 6

Vous devez fusionner la branche emojiSurprise créée précédemment à la branche master afin de récupérer sur la branche master votre nouvel emoji. La fusion devra se faire sans le mode "Fast forward".

### Exercice 7

Vous devez récupérer et fusionner la branche miseenformecss depuis le dépôt distant https://github.com/alvinberthelot/evaluate-git-noob.
