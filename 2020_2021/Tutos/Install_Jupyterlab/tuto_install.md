# Installation de Jupyter Lab

Voici les étapes à suivre pour installer Jupyter Lab. **Attention** si vous avez déjà installé Python, il vous faut commencer par le désinstaller.

Ce tutoriel vous est proposé par Camille Marcel Javel, étudiant en L1 Informatique.


## Désinstaller votre Python...

et supprimer le dossier Python s'il existe 

![effacer dossier](00_clean.png)

## Installation de Jupyter Lab


### Télécharger Python...

Sur le site officiel : http://python.org/downloads/ prenez la dernière version, en tout cas une version $\geq$ 3.6

![etape 1](install_01.png)

### Lancer l'installation...

**Attention** bien cocher la case `Add Python ... to PATH` puis cliquer sur `Install Now`

![etape 2](2.png)

### Installation réussie...

Vous pouvez fermer la fenêtre de Setup

![etape 3](3.png)

### Lancer une invite de commandes...

Il y a plusieurs façons de faire. En voici une décrite par l'auteur de ce tuto :

![etapes 4 et 5](4_et_5.png)


Ou alors (windows 10) : rechercher "Invite de commandes" dans l'outil de recherche en bas du bureau, comme ci-dessous :

![etapes 4 et 5 bis](4_et_5bis.png)


### Taper la commande pour installer...

Dans l'invite de commandes, taper la commande :

```bash
pip install jupyterlab
```

**Attention** `jupyterlab` est en 1 seul mot !

![etape 6](6.png)


### Etape OPTIONNELLE : mettre à jour pip

**Vous pouvez passer cette étape**. Elle sert à mettre à jour votre outil `pip` s'il ne l'est pas. 

![etape 7](7.png)

### Lancer Jupyter Lab...

Toujours dans l'invite de commandes, taper la commande suivante :

```bash
jupyter lab 
```

**Attention** cette fois il y a bien une espace entre `jupyter` et `lab`

![etape 8](8.png)

Cela devrait vous ouvrir votre navigateur avec une page similaire à :

![etape 9](fenetre_jupyter.png)
