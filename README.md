🇬🇧 Version anglaise disponible : [README_EN.md](README_EN.md)


# Cinéma Club 108 - Page Produit

## Description

Cette page web présente la structuration d’une page produit pour une boutique en ligne dédiée à un cinéma appelé **Club 108**.  
Elle affiche les actualités, séances, programmation, ainsi que les informations pratiques du cinéma.

---

## Contenu principal

- **Header** : logo, titre et menu de navigation principal avec liens vers différentes sections du site.
- **Main** :  
  - Une actualité principale avec image et texte  
  - Un tableau des séances programmées  
  - L’adresse du cinéma avec données structurées (Schema.org)  
  - Une publication avec image et bouton d’action  
  - Une section « Dans la semaine » présentant plusieurs événements avec images  
- **Footer** : liens utiles et logo du cinéma

---

## Technologies utilisées

- HTML5 sémantique  
- Microdata Schema.org pour le balisage sémantique des données d’adresse  
- Attributs ARIA pour l’accessibilité  
- Responsive design avec `srcset` et `sizes` pour les images  
- CSS externe (fichiers `default.css` et `style.css`) pour la mise en forme

---

## Organisation des fichiers

/devoir-05/
/css/
default.css
style.css
/img/
logo.png
cinema1000.webp
cinema2.webp
theatre2.webp
fauteuils.webp
index.html (page principale)
README.md (ce fichier)

---

## Instructions

1. Ouvrir `index.html` dans un navigateur moderne pour visualiser la page.  
2. Modifier les contenus HTML selon les besoins (titres, images, textes, horaires).  
3. Adapter les styles CSS dans les fichiers liés pour personnaliser l’apparence.

---

## Accessibilité

- Navigation principale et pied de page sont accessibles via ARIA  
- Images disposent d’attributs `alt` descriptifs  
- Utilisation des balises sémantiques pour une meilleure compréhension par les lecteurs d’écran

---

## Améliorations possibles

- Ajouter un vrai système de réservation fonctionnel  
- Dynamiser les horaires et les séances via JavaScript ou backend  
- Optimiser les performances avec un lazy loading des images  
- Ajouter un formulaire de contact fonctionnel  
- Étendre le microdata pour mieux référencer les films et événements

---

## Auteur

Vanessa PAGANOTTO 

---

## Licence

Ce projet est sous licence MIT.
