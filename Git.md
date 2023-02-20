Créé par Linus Torvalds,
`xcode-select --install` pour installer les tools sur macOS,
système de stockage decentralisé (= si un noeud tombe, le réseau ne tombe pas) comme la blockchain ou les torrent.
On peut remonter a des instanés,
successeur de SVN,

## Commandes
### git-init
```bash
git init
```
Permet d'initialiser un repo dans le dossier actuel

### git-status
```shell
git status
```
Donne l'état du repo git actuel

### git-add
```bash
git add fichier.ext
git add -A
```
Ajoute des fichiers au prochain 'commit',
`-A` ajoute tous les changements

### git-commit
```bash
git commit
```
Enregistre le changement, ouvre un editeur de texte pour mettre un commentaire sur le commit actuel (par défaut: `vim`). `-m "MESSAGE"` pour spécifier le message directement.

## git-config
```bash
git config --global user.name "Guillaume P"
git config --global user.email "yaume@ntymail.com"
```
permet de configurer git, `--global` applique le reglage sur tous les repos