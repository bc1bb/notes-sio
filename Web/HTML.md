Les balises ont toujours une ouverture et une fermeture (sauf `br`, `hr`, `img` et d'autres balises qui n'ont pas de contenu).

Les balises peuvent avoir un ou plusieurs attributs.

Les fermetures des balises `body` et `html` doivent se suivre.

-> [Bible HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/)

# Balises de bases
## Commentaire
Pour placer un commentaire en html il faut utiliser:
```html
<!-- CI GÎT UN COMMENTAIRE -->
```

## Titres
Les balises sont sous la formes `h1`, `h2`, `h3`, `h4`, `h5`, `h6`. `h1` est le plus important, `h6`, le moins important

## Listes
### Désordonnée
```html
<ul>
	<li>Premier element</li>
	<li>Deuxieme element</li>
</ul>
```

### Ordonnée
#### Attribut
- `type` (facultatif): permet de changer le type de la liste (`I` pour des chiffres romains, `A` pour une liste en lettres, ...)
```html
<ol>
	<li>Premier element</li>
	<li>Deuxieme element</li>
<ol>
```


## `html`
Déclaration d'une page HTML

### Attributs
- `lang` (facultatif): Déclare la langue de la page.

## `head`
Tete de la page, contient des meta données qui ne seront pas affichées au client

### `title`
Un seul par page, élément obligatoire du `head`, défini le titre de la fenêtre.

### `meta`
Déclare une meta donnée, peut servir a déclarer l'encodage ou le viewport, ...

## `body`
Corps de la page, contient la page en elle-même

## `p`
Affiche un paragraphe

## `img`
Affiche l'image dans l'attribut `src`

### Attributs
- `src` (obligatoire): Chemin vers l'image
- `alt` (facultatif): Texte alternatif (pour lecteurs d'écrans),
- `title` (facultatif): Titre de l'image (affiché quand on passe la souris).

## `strong`
Passe le texte en gras.

## `i`
Passe le texte en italique.

## `div`
Permet de placer n'importe quoi dedans, utilisé pour placer du style a un endroti de la page web

## `span`
Permet de déclarer une division au sein d'un paragraphe, utile pour la mise en forme d'une partie d'un paragraphe

## `header`
Contient le haut de la page, en général le logo et des menus,

## `footer`
Contient le bas de la page, en général des liens sociaux, des politiques de confidentialité, ...

## `nav`
Sert a créer une barre de navigation entre les differentes parties du site.

## `main`
Sert a déclarer la partie principale de la page

## `section`
Sert a déclarer une section d'une page

## `pre`
Sert a inserer du texte pre-formatté, le contenu garde exactement la meme mise en forme que dans le code.

## `a`
Permet d'ajouter un lien vers une page ou une partie de la page actuelle

### Attributs
- `href` (obligatoire): cible du lien,
- `target` (facultatif): permet d'ouvrir le lien dans une nouvelle page quand la valeur est `"_blank"`

## `video`
Sert a insérer une vidéo dans une page

### Attributs
- `src` (obligatoire): Donne le chemin vers la vidéo

