<<<<<<< HEAD
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
## Les liens

Pour créer un lien, vous devez placer le texte du lien entre crochets suivis de l'URL entre parenthèses :

"[TEXTE] (LIENS)"

Cela donne:

Rendez-vous sur  [Linkedin](https://www.linkedin.com/) pour vous créer un espace professionnel et donner accès à votre profil à vos potentiels futurs employeurs ou collègues !

Cela permet donc d'insérer des liens dans votre texte en Markdown sans recourir au code HTML.
>>>>>>> 7652b68a63e24d9e76734ff98a49cbbb1e49b233
