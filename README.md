# Arbre généalogique

Lecteur d'arbre généalogique en une seule page HTML, sans dépendance ni serveur.
Recherche par nom, fiche individuelle, ascendance, descendance, calcul de lien de
parenté, export de l'ascendance en image PNG ou SVG, et un mode édition qui écrit
directement dans ce dépôt.

## Données

`tree.ged` est le fichier de données, chargé par la page au démarrage. Il ne
contient que **noms, prénoms, sexe, dates de naissance et de décès, et liens
familiaux**. Aucune autre information (lieux, professions, notes, e-mails,
adresses, sources) n'y figure. Les dates de décès sont incluses : elles ne
concernent que des personnes déjà décédées et ne posent pas de problème de
confidentialité pour les vivants.

## Édition

Le bouton « Édition » de la page permet d'ajouter une personne, la relier à une
autre (enfant, parent, conjoint·e), modifier ou supprimer. « Enregistrer sur
GitHub » écrit `tree.ged` via l'API GitHub après saisie d'un jeton à droit
d'écriture ; le jeton reste dans le navigateur. GitHub Pages redéploie ensuite
le site en une minute environ.

Chaque enregistrement est un commit : l'historique du dépôt garde toutes les
versions du fichier.

## Utilisation hors ligne

Ouvert comme simple fichier local, `index.html` utilise une copie des données
intégrée à la page (le mode édition GitHub n'a alors pas de cible).

## Publication

Site statique : GitHub Pages sur la branche `main`, dossier racine.
