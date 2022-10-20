###Exercice #01 — travailler avec Git.

###Pour cet exercice vous devez noter les commandes que vous avez exécutées, vous devrez donc utiliser Git en ligne de commande (CLI). Notez les commandes Git sous leur point. Remettez un dossier complet incluant les trois répertoires Git et ce fichier texte.

##Numéro 1 : Commande de base

1.	Créez un dépôt git en local
```
Commandes ici
```
2.	Créez les 3 fichiers suivant et y mettre quelques lignes de texte
	a.	index.html
	b.	 style.css
	c.	 main.js

```
Commandes ici
```
3.	Vérifiez l’état de votre dépôt
```
Commandes ici
```

4.	Créez un commit avec ces trois fichiers
```
Commandes ici
```

5.	Faites la commande suivante : 
`` git status >> git_exercice1.log && git log >> git_exercice1.log``
6.	Faites un commit pour ajouter le nouveau fichier créer (git_exercice1.log)
```
Commandes ici
```

## Numéro 2 : Travailler avec un distant (remote)

1.	Créez un dépôt nommé « n61-remote-git » sur votre compte Github.com. Si vous n’avez pas de compte, c’est le bon moment pour en créer un…
2.	Clonez le dépôt vide en local
```
Commandes ici
```
3.	Créez les 3 fichiers suivant et mettez-y quelques lignes de texte
	a.	index.html
	b.	 style.css
	c.	 main.js

```
Commandes ici
```
4.	Vérifiez l’état de votre dépôt
```
Commandes ici
```
5.	Créez un commit avec ces trois fichiers
```
Commandes ici
```
6.	Mettez à jour votre dépôt distant
```
Commandes ici
```
7.	Faites une capture d’écran de votre dépôt distant et ajoutez le fichier image dans votre commit.
```
Commandes ici
```

##Numéro 3 : Travailler en équipe
1.	Forkez le projet https://github.com/emmacharp/exercice_git_equipe sur votre compte github. 

2.	Clonez le dépôt en local
```
Commandes ici
```
3.	Configurez le dépôt upstream pour qu’il pointe vers le dépôt que vous avez forké (et non votre dépôt distant)
```
Commandes ici
```
4.	Exécutez la commande ``git remote -v`` et copiez le contenu ici :
```
Contenu copié ici
```
5.	Remplacez « Jonathan Martel » dans le fichier main.js et inscrivez-y votre nom. 
6.	Commitez vos changements, mettez à jour votre distant (remote)
```
Commandes ici
```


7.	Pour générer un conflit de code, ajoutez un nouveau remote avec lequel nous allons jouer en utilisant la commande suivante :  
`` git remote add depotconflit https://github.com/emmacharp/exercice_git_equipe_conflit``
8.	Faite la mise à jour et la fusion de votre dépôt local avec le nouveau dépôt distant :  
``git pull depotconflit master``  
Et copiez la réponse du terminal ici :  
```
Réponse copiée ici
```
9.	Réglez les conflits, finalisez la fusion et mettez à jour votre distant (push sur origin)
10.	Sur Github.com, ouvrez une demande de pull-request vers https://github.com/emmacharp/exercice_git_equipe

