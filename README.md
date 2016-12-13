# TP-C-3

## Les étapes pour contribuer à un projet :

### Pour démarrer sur un projet

- Faire un fork sur GitHub

- Cloner le fork sur votre PC avec la commande :
```
	git clone <adresse du fork>
```

- Aller dans le dossier nouvellement créé :
```
	cd <nom du depot>
```

- Configurer le remote upstream avec la commande :
```
	git remote add upstream <adresse du dépôt original>
```


### Pour faire une modification

- Créer une nouvelle branche avec la commande :
```
	git checkout -b <nom de la branche>
```

- Faire les modifications

- Ajouter les fichiers modifiés avec la commande :
```
	git add <chemin vers le fichier 1> <chemin vers le fichier 2> ...
```

- Faire un commit avec la commande :
```
	git commit -m "<message de commit>"
```

- Push le commit sur le fork avec la commande :
```
	git push origin <nom de la branche>
```

- Faire une pull request sur GitHub sur develop

### Pour se mettre à jour sur l'état du dépot

- Se mettre à jour sur le dépôt original avec la commande :
```
	git fetch upstream
```

- Aller sur la branche develop locale avec la commande :
```
	git checkout develop
```

- Merger l'état du dépôt original avec la commande :
```
	git merge upstream/develop
```

- Push les modifications sur le fork avec la commande :
```
	git push origin develop
```



