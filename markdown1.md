<<<<<<< HEAD
<<<<<<< HEAD
=======
## Les listes numérotée.
Pour créér une liste numérotée (ou liste ordonnée), c'est finalement très intuitif:
Commencez la ligne par un nombre suivi d'un point. Pour que votre *mardown* soit plus lisible, je vous conseille 
d’ordonner proprement votre liste. Mais ce n’est pas nécessaire pour le rendu HTML. 
Comme vous pouvez le voir dans l’export html, la seule différence avec la liste non ordonnée est que 
la balise englobant les éléments est `ol` et plus `ul`. C’est le navigateur qui se charge d’ajouter les nombres
 pour ordonner la liste.

```


1. Ceci est un premier élèment.
2. Ceci est un deuxième élèment.
98. Ceci est un troisième élèment et ce sera bien le chiffre '3' qui sera pucé au lieu du '98' qui me sert à déclarer ma puce.
150. Ceci est un dernier élément, et ce sera bien le chiffre '4' qui sera pucé au lieu du '150'


```
Pour un résultat:

1. Ceci est un premier élèment.
2. Ceci est un deuxième élément.
98. Ceci est un troisème élèment et ce sera bien le chiffre '3' qui sera pucé au lieu du '98' qui me sert à déclarer ma puce.
150. Ceci est un dernier élèment, et ce sera bien le chiffre '4' qui sera pucé au lieu du '150'.

En langage *HTML*, on utilisera:

```


<ol>
	<li>item</li>
	<li>item</li>
	<li>item</li>
</ol>


```

Pour un résultat:

<ol>
	<li>item</li>
	<li>item</li>
	<li>item</li>
</ol>





=======
>>>>>>> 707b8c748c96de156503632b8fff404a63c7707a
## Les liens

Pour créer un lien, vous devez placer le texte du lien entre crochets suivis de l'URL entre parenthèses :

"[TEXTE] (LIENS)"

Cela donne:

Rendez-vous sur  [Linkedin](https://www.linkedin.com/) pour vous créer un espace professionnel et donner accès à votre profil à vos potentiels futurs employeurs ou collègues !

Cela permet donc d'insérer des liens dans votre texte en Markdown sans recourir au code HTML.
<<<<<<< HEAD
=======
# Le Markdown, comment ça marche?

C'est un petit langage très simple qui permet d'écrire du HTML de façon raccourcie. On peut s'en servir sur certains forums ou pour rédiger des documentations (incontournable sur GitHub).

Les créateurs de Markdown trouvaient que ce n'était pas vraiment pratique de devoir mettre en forme manuellement des textes en HTML (ou, pire, en bbCode). Imaginez, vous voulez poster un message sur un forum qui accepte uniquement le HTML et vous voulez écrire une liste à puces. Vous allez devoir écrire à la main…

```html
<ul>
	<li>Le contenu de ma première puce</li>
	<li>Le contenu de ma seconde puce</li>
	<li>Et encore une autre puce</li>
</ul>

```

… et ça, juste pour faire une liste à puces, il faut avouer que ça devient vite lourdingue !

John Gruber et Aaron Swartz ont donc créé un petit langage très simple appelé le Markdown. L'idée est de pouvoir mettre en forme du texte sans avoir besoin de recourir à la souris… et sans avoir besoin de taper à la main des balises HTML toutes les 5 secondes.

Si vous aussi vous souhaitez mettre en forme vos messages rapidement et proprement, suivez le guide ! Vous aurez appris Markdown avant d'avoir eu le temps de dire « ouf » !


## Liste à puces

Créer des listes en Markdown est un vrai bonheur, vous allez voir qu'il n'y a rien de plus simple ! Voici la procédure pour créer une liste:

```
* Une puce
* Une autre puce
* Et encore une autre puce !

```
### Résultat

* Une puce
* Une autre puce
* Et encore une autre puce !

>>>>>>> origin/Pierre
=======
>>>>>>> 7652b68a63e24d9e76734ff98a49cbbb1e49b233
>>>>>>> 707b8c748c96de156503632b8fff404a63c7707a
