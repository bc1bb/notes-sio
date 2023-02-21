Permet d'ajouter du style a des pages HTML.

# Selecteurs
`*` permet d'appliquer un style sur toute la page,
`h1` permet d'appliquer un style sur toutes les balises `<h1>`,
`.titre` permet d'appliquer un style sur tous les éléments de classe `titre`,
`#titre` permet d'appliquer un style sur un tous les éléments d'id `titre`,

# Regle
```css
selecteur {
	props: valeur
}
```

---

```css
a:visited {
	color: wheat;
}```
Le code si dessus applique la couleur `wheat` pour les liens deja visités

---

```css
span[title="Titre"] {
	color: brown;
}```
Le code si dessus applique la couleur `brown` sur les <span> qui ont pour titre `Titre`