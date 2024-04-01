# Configuration du site.

## Première installation

```bash
$ bash tools/init
```

Cette commande va:

- S'assure que le code est au dernier niveau validé
- supprime les fichiers d'exemple
- construction des fichiers js
- création d'un commit pour enregistrement des MAJ

installation des dépendances.

```bash
$ bundle
```

## Configuration

Modification des variables dans **\_config.yml**.

- url
- avatar
- timezone
- lang

## Contacts RSE

A modifier dans **\_data/contact.yml**

## Lancement du serveur

Pour lancer localement le site.

```bash
$ bundle exec jekyll s
```

Ceci permet de publier sur [Local dev](http://127.0.0.1:4000).

## Deployer via GitHub Actions

Actions.

- Les comptes gratuit doivent être on public
- Si **Gemfile.lock** a été commit dans le repo et que la machine locale n'est pas Linux.

```bash
$ bundle lock --add-platform x86_64-linux
```

Puis, configurer le service _GitHub Pages_.

1. Dans le repo, aller dans _Settings_ puis _Pages_. Puis dans la section **Source** (en dessous de _Build and deployment_), selectionnet _GitHub Actions_.
2. Push code pour initier le build du site. L'url est fournie par GitHub.
