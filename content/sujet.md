+++
Categories = []
Tags = []
date = "2016-10-07T11:28:58+02:00"
title = "Sujet de TP"

+++

# Mémo

## Hugo

Création d'un article

    ./bin/hugo.exe new nom-de-l-article.md

 Serveur de dev

    ./bin/hugo.exe server --buildDrafts -w

## Markdown

    # Titre 1
    ## Sous Titre 1
    * Liste à puce, item1
    * Liste à puce, item2
    *Italique*
    **Gras**
    ***Gras et italique***

# Questions de TP

## TP 00 - Configuration

* Configurer son nom, prénom et email
* Générer une clé ssh pour son poste de travail
* Ajouter une clé ssh à son profil GitLab

## TP 01 - Les débuts

* Initialiser un répertoire de travail dans un dépôt local Git.
* Cloner le projet GitLab « TP » du groupe GitLab « Formation ».
* En binôme ou en trinôme, définir un sujet d’article et un nom de fichier associé.
* Créer puis indexer l’article. Faire un premier commit.
* Partager l’article.
* Récupérer les articles depuis son poste

## TP 02 - Gestion des conflits

* Modifier, sur son poste,  l’article de son groupe de travail.
* Partager ses modifications à plusieurs reprises.
* Expérimenter Git Bash, Git GUI et le plugin Eclipse

## TP 03 - Ignorer des fichiers

* Modifier .gitignore pour que les fichiers générer par Hugo soient ignorer par Git
* Nettoyer son répertoire de travail.

## TP 04 - Manipulation des zones de travail Git

* Renommer son article, l’indexer et faire un ‘commit’
* Annuler l’action précédente
* Déplacer l’article dans un nouveau répertoire et indexer la modification.
* Annuler l’action précédente
* Modifier le contenu de son article
* Annuler l’action précédente

## TP 05 - Manipulation des branches

* Créer une branche quelconque
* Vérifier l’existence de cette branche
* Changer de branche
* Créer une autre branche (nom=login Windows) et se placer directement dessus.
* Supprimer la branche quelconque

## TP 06 - Fusion de branches locales et distantes

* Effectuer plusieurs commits sur la branche créée précédemment.
* Pousser cette branche sur le serveur GitLab
* Fusionner cette branche avec la branche master
* Récupérer les branches des autres participants
* Fusionner la nouvelle branche avec la branche origin (serveur)

## TP 07 - Tags : Manipulation et partage

* Placer un tag sur un commit
* Pousser ce tag sur le serveur
* Récupérer et lister les tags des participants

### Règle de nommage à respecter pour Hawaii : vX.Y.Z.SUFFIXE
    Exemples :
      v4.5.67
      v2.2
      v2.3.4.RC1
      v2.3.4.RELEASE

## TP 08 - Visualiser l’historique

* Afficher l’historique des commits.
* Afficher la différence entre deux commits.
* Identifier l’auteur des différentes parties de son article.
* Expérimenter l’affichage de l’historique avec Git Bash, Gitk et le plugin Eclipse.

## TP 09 - Remonter le temps

* Se positionner dans sa branche
* Repositionner HEAD dans un état antérieur (commit, tag)
* Prendre un commit quelconque et l’appliquer localement
* Choisir un commit, puis supprimer tous les commits postérieurs à celui-ci.

## TP 10 - Rebase de branche

* Créer une branche locale de type feature à votre nom
* Effectuer plusieurs commits
* Réappliquer les commits dans master via un rebase

## TP 11 - Mettre de côté ses développements

* Effectuer de nouvelles modifications (sans commit) sur sa branche.
* Suite à une alerte, mettre de côté son travail et basculer sur la branche master pour y effectuer une modification (sur le même fichier).
* Une fois la modification urgente livrée (commit), reprendre son travail mis de côté.

## TP 12 - Réécrire l'histoire !

 * Fusionner deux commits en un seul.
 * Changer le commentaire d’un commit
