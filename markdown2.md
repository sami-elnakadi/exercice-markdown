<<<<<<< HEAD
## Coloration syntaxique

Ici nous souhaitons colorer la syntaxe d'une ligne de code provenant d'un autre language de programmation.

Partons de ceci: 

<script type="text/javascript">
    alert("Hello!");
</script>


Nous pouvons voir que la syntaxe est incolore, et donc peu lisible, voyons maintenant comment rendre la chose plus pratique!

Il faut d'abord préciser le type de code utiliser dans l'extrait que nous avons sélectionné.
Ensuite, nous allons créer une liste ul - li, pour "isoler" ce bout de code du reste.

```html

	<ul>
		<li> <script type="text/javascript">
    alert("Hello!");
		</script>
		</li>
	</ul>
```
ou encore en ajoutant 

"``` type de code

votre code en commencant chaque ligne par >
et ferme avec ```

Ce qui donne ceci: 

```javascript
><script type="text/javascript">
>    alert("Hello!");
>		</script>
```
=======
## Les images statiques

Pour afficher l'image, vous devez simplement mettre un point d'exclamation devant les premiers crochets. Ce qui se trouve entre les crochets est le nom de l'image. Puis l'url de l'image se trouve entre parenthèses.

```text

![img](https://www.laurasmulders.com/wp-content/uploads/2016/08/M0JJ0v8.png)

```
![img](https://www.laurasmulders.com/wp-content/uploads/2016/08/M0JJ0v8.png)



>>>>>>> origin/Pierre
