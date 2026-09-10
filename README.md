# Arbre généalogique

Lecteur d'arbre généalogique en une seule page HTML, sans dépendance ni serveur.
Recherche par nom, fiche individuelle, ascendance, descendance, calcul de lien de
parenté, et export de l'ascendance en image PNG ou SVG.

## Données

La version publiée ne contient **que les noms, prénoms et dates de naissance**.
Toutes les autres informations présentes dans l'export d'origine (décès, lieux,
professions, notes, e-mails, adresses, sources) ont été retirées avant publication.
Le jeu de données restreint se trouve dans `fullExport.public.ged`.

## Utilisation

Ouvrir `index.html` dans un navigateur. L'arbre est intégré à la page ; rien
n'est téléchargé et aucune donnée ne quitte le navigateur. Le bouton
« Charger un fichier .ged » permet d'ouvrir un autre export GEDCOM à la place.

## Publication

Site statique : n'importe quel hébergement de fichiers convient. Sur GitHub Pages,
activer Pages sur la branche `main`, dossier racine ; l'URL sert alors `index.html`.
