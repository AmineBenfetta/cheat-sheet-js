# Cheat-cheet/notes sur les variables en JavaScript. 

## Qu'est-ce qu'une *variable* ? 

>Une variable est un "stockage nommé" pour les données.

 (source:*javascript.info*) Concrétement une variable en JavaScript sert a stocker des données et a les modifier par la suite. 

Pour initier une variable c'est très simple, il suffit juste d'utiliser le terme "**let**" anciennement "*var*". 

exemple : `let message;` 

puis on peux y ajouter des données en utilisant le signe " = ". 

exemple : `let message; message = 'Hello';` Cela a pour effet de stocker la chaîne de caractères 'Hello' dans la variable cet à dire qu'en appelant la variable "message" nous auront 'Hello' en réponse. 

On peux aussi déclarer plusieurs variables dans une seule ligne. Exemple : `let user = 'Jhon', age = 25, message = 'Hello';`  Mais ce n'est pas vraiment recommandé. 

**! Déclarer deux fois déclanche une erreur.** Une variable ne doit être déclarée qu'une seule fois, pour modifier une variable il ne faut donc pas la redéclarer comme ceci:
`let message = "This"; let message = "That";` mais plutôt la modifié sans la redéclarer comme cela : `let message = "This"; message = "That";`. 

### Nommage de variable 

**Il existe des limitations pour le nommage d'une variable en JavaScript.**
1. Le nom ne doit contenir uniquement des lettres, des chiffres, des symboles $ et _.
2. Le premier caractère ne doit pas être un chiffre. 

