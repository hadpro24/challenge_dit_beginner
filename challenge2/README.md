<h1 align="center">
  Challenge #1
</h1>

## Challenge 1
Afficher l’ensemble des nombres premiers inferieurs a 100.

## Challenge 2
Afficher la liste du 10e au 20e nombre premier:  ```:[31, 37, 41, 43, 47, 53, 59, 61, 67, 71].```

<h1 align="center">
  Quiz #2
</h1>

## Quiz 1
Chaque élément d'une liste est associé à son index, c'est à dire à sa position.
```
Vrai
Faux
```

## Quiz 2
Pour transformer une chaîne de caractères en liste, j'utilise la méthode suivante:

```
 .list() 
 .to_list() 
 .split() 
 ```

## Quiz 3
Après ces instructions, de quel type est la variable c ?
```python
a = 8
b = 3
c = a / b
```

## Quiz 4
Quelle est la variable de type str (chaîne de caractères) parmi les choix suivants ?
`3 - 3.1 - "3"`

## Quiz 5
Quelle est la différence entre entrer une variable dans l'interpréteur interactif et utiliser la fonction print ?
```
1 - Aucune
2 - Dans l'interpréteur interactif, toutes les variables apparaissent entourées de guillemets.
3 - La fonction print est dédiée à l'affichage, l'interpréteur au débuggage.
```

## Quiz 6
De quoi doit être composée une condition au minimum ?
```
1 - D'un bloc if
2 - D'un bloc if et elif
3 - D'un bloc if et else
```

## Quiz 7
Considérant les instructions ci-dessous, si variable vaut 2.8, quel va être le résultat obtenu ?
```python
if variable >= 3:
    print("1")
elif variable < -1:
    print("2")
else:
    print("3")
```
```
1 - Afficher 1.
2 - Afficher 2.
3 - Afficher 3.
4 - N'afficher rien.
```
## Quiz 8
Considérant le prédicat combiné ci-dessous, dans quel cas sera-t-il True (vrai) ?

`predicat_a and predicat_b`
```
1 - predicat_a est vrai, peu importe predicat_b.
2 - predicat_b est vrai, peu importe predicat_a.
3 - L'un d'eux est vrai, peu importe l'autre.
4 - predicat_a et predicat_b sont tous deux vrais.
```

## Quiz 9
Comment Python identifie-t-il les instructions formant un bloc (par exemple à l'intérieur d'une condition) ?

```
1 - Grâce à l'indentation
2 - Grâce aux accolades ({}) entourant le bloc
3 - Grâce aux deux points en début de bloc
```

## Quiz 10
Quel est l'avantage de la boucle `while` sur la boucle `for` ?

```
1 - Aucun.
2 - Elle est préférable pour parcourir des séquences.
3 - Elle fait la même chose en moins de lignes de code.
4 - Elle crée rarement de boucle infinie.
5 - Elle est plus utile pour vérifier une condition.
```

## Quiz 11
Quel est l'avantage de la boucle `for` sur la boucle `while` ?

```
1 - Elle est préférable pour parcourir des séquences.
2 - Elle est plus utile pour vérifier une condition.
3 - C'est l'unique façon de parcourir des séquences.
```

## Quiz 12
Quelle est la différence entre le mot-clé break et continue ?

```
1 - break interrompt la boucle immédiatement alors que continue passe au prochain tour de boucle.
2 - continue interrompt la boucle immédiatement alors que break passe au prochain tour de boucle.
3 - Les deux mot-clés font exactement la même chose en interrompant la boucle immédiatement.
```

## Quiz 13
Sachant la définition de fonction ci-dessous, quel est l'appel INVALIDE parmi les choix suivants ?

``def table(nombre, maximum=10):```
```
1 - table(5, 20)
2 - table(12, maximum=5)
3 - table(8)
4 - table(maximum=15, nombre=4)
5 - table(7, entier=30)
```

## Quiz 15
Quelle est l'utilité des fonctions `lambda` par rapport aux fonctions définies par `def` ?

```
1 - Elles s'exécutent plus rapidement.
2 - On peut en créer avec une syntaxe très légère.
3 - Elles permettent des fonctionnalités inaccessibles aux fonctions définies par def
```

## Quiz 16
Qu'est-ce qu'un module en Python ?

```
1 - Un fichier contenant du code Python sans extension particulière.
2 - Un fichier contenant du code Python avec l'extension .py
3 - Un répertoire contenant des fichiers Python
```

## Quiz 17
Dans quel cas l'instruction ci-dessous lèvera une exception (une erreur) ?

`annee = int(entree)`
```
1 - La variable annee n'existe pas.
2 - La variable entree est une chaîne de caractères.
3 - La variable entree ne peut être convertie en nombre.
```
## Quiz 18
Que renverra l'instruction suivante, partant du principe que la variable chaine contient une chaîne de caractères (str) ?

`chaine[:3]`

```
1 - Le troisième caractère de la chaîne
2 - Le quatrième caractère de la chaîne
3 - Les trois premiers caractères de la chaîne
```

## Quiz 19
Peut-on modifier un caractère d'une chaîne de caractères (variable chaine dans cet exemple) grâce à l'instruction suivante ?

`chaine[0] = "A"`
```
1 - Oui
2 - Non
```

## Quiz 20
Que peut contenir une liste (objet de classe list) ?
```
1 - Un nombre indéterminé d'objets du même type
2 - Un nombre indéterminé d'objets sans type particulier
3 - Un nombre indéterminé d'objets tant qu'aucun ne se trouve plus d'une fois dans la liste
```

## Quiz 21
On peut accéder à un élément d'une liste en utilisant les crochets entourant un entier (un indice). Dans quelle circonstance l'indice menant à un élément est-il modifié ?

```
1 - Jamais, les indices ne changent pas après la création d'une liste.
2 - Si on change l'ordre de la liste.
3 - Seulement si on supprime certains éléments contenus dans la liste.
```

## Quiz 22
Que renvoie la plupart des méthodes de liste (classe list) comme append, insert ou remove ?

```
1 - L'élément ajouté ou retiré de la liste
2 - L'indice de l'élément ajouté ou retiré de la liste
3 - La liste modifiée
4 - Rien (None)
```

## Quiz 23
Peut-on modifier un élément de liste (variable liste dans l'exemple) en utilisant l'instruction suivante ?

`liste[0] = "quelque chose"`
```
1 - Oui
2 - Non
```

## Quiz 24
Quelle est la différence entre les listes (classe list) et les tuples (classe tuple) ?

```
1 - On ne peut pas modifier les tuples une fois créés.
2 - Les tuples ne peuvent pas contenir plusieurs types d'éléments.
3 - On ne peut pas parcourir des tuples.
```

## Quiz 25
Après ces instructions, combien d'éléments contiendra la variable ma_liste ?
```python
ma_liste = [1, 2, 4, 8, 16, 32, 64]
ma_liste = [n for n in ma_liste if n < 16]
```
``` 3 - 4 - 5 - 6
```

## Quiz 26
Comment sont stockés les éléments dans un dictionnaire ?

```
1 - Sans aucun ordre
2 - Sans ordre sauf si on utilise des clés entières
3 - Dans l'ordre dans lequel on les ajoute
```

## Quiz 27
Si adresses est un objet dictionnaire, qu'obtiendra-t-on en entrant l'instruction ci-dessous ?

```python
for item in adresses: print(item)
```
```
1 - Les clés du dictionnaire
2 - Les valeurs du dictionnaire
3 - Les clés et valeurs du dictionnaire par paire (tuple)
```

## Quiz 28
Sachant que la variable dictionnaire est un dictionnaire, quelle est la différence entre les deux instructions suivantes ?

```python
del dictionnaire["cle"]
dictionnaire.pop("cle")
```
```
1 - Si la clé n'existe pas, l'exception levée n'est pas la même.
2 - La méthode pop retourne la valeur correspondant à la clé supprimée.
3 - La méthode pop peut aussi être utilisée pour supprimer une valeur du dictionnaire.
```

## Quiz 29
A quoi sert le mot-clé `with` utilisé quand on lit ou écrit dans un fichier ?

```
1 - Il permet de capturer toutes les exceptions qui pourraient se produire.
2 - Il s'assure que le fichier est fermé, même s'il se produit des erreurs dans le bloc.
3 - Il permet de stocker des objets dans des fichiers.
```

## Quiz 30
Après le code suivant, combien d'éléments contiendra liste1 ?
```python
liste1 = [1, 2, 3]
liste1.append(8)
liste2 = liste1
liste2.append(19)
```
``` 3 - 4 - 5 ```










