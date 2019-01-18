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
