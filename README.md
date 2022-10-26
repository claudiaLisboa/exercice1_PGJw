###Exercice #01 — travailler avec Git.

###Pour cet exercice vous devez noter les commandes que vous avez exécutées, vous devrez donc utiliser Git en ligne de commande (CLI). Notez les commandes Git sous leur point. Remettez un dossier complet incluant les trois répertoires Git et ce fichier texte.

##Numéro 1 : Commande de base

1.	Créez un dépôt git en local

Commandes ici

<img width="726" alt="1" src="https://user-images.githubusercontent.com/21189063/197417372-ce9d753a-0b7c-4588-adbe-9821493d0cbb.png">
<img width="1374" alt="2" src="https://user-images.githubusercontent.com/21189063/198150511-749cd047-a939-4349-8c80-8b1812f85adb.png">
<img width="757" alt="3" src="https://user-images.githubusercontent.com/21189063/198150536-83a5d8d8-4087-450a-81cd-37127d014c46.png">
<img width="771" alt="4" src="https://user-images.githubusercontent.com/21189063/198150702-a698b04a-8ce7-4dc5-89d6-0478d8fa1423.png">

```
2.	Créez les 3 fichiers suivant et y mettre quelques lignes de texte
	a.	index.html
	b.	 style.css
	c.	 main.js

Commandes ici

<img width="824" alt="5" src="https://user-images.githubusercontent.com/21189063/198151156-173cab8e-392f-482a-8d80-ed3d58d7b727.png">
<img width="856" alt="6" src="https://user-images.githubusercontent.com/21189063/198151651-adc348ae-20b7-462b-b63c-c336b433fc57.png">
<img width="966" alt="7" src="https://user-images.githubusercontent.com/21189063/198151665-d6493086-9dc2-4a28-aa5b-a73b3c48755c.png">
<img width="951" alt="8" src="https://user-images.githubusercontent.com/21189063/198153802-02dec25a-8ae9-4157-83f3-9cf45d8ab99e.png">


3.	Vérifiez l’état de votre dépôt
```
Commandes ici

<img width="782" alt="9" src="https://user-images.githubusercontent.com/21189063/198153852-83ad1e29-f019-4492-856b-f4d56e009759.png">


4.	Créez un commit avec ces trois fichiers
```
Commandes ici

<img width="1020" alt="10" src="https://user-images.githubusercontent.com/21189063/198154708-1b727c5e-0d36-4385-8c70-a8504d8c45dd.png">


5.	Faites la commande suivante : 
`` git status >> git_exercice1.log && git log >> git_exercice1.log``

<img width="1045" alt="11" src="https://user-images.githubusercontent.com/21189063/198155994-aa6ff07d-3777-4b59-965a-3d89e22853fb.png">


6.	Faites un commit pour ajouter le nouveau fichier créer (git_exercice1.log)
```
Commandes ici

<img width="996" alt="12" src="https://user-images.githubusercontent.com/21189063/198157359-6ba60229-e5e2-453e-b0a3-fe6615925f17.png">


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

