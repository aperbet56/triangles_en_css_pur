## TRIANGLES EN CSS3 🔺

## Le challenge

Création d'un carré contenant quatre triangles de couleurs différentes en HTML5 et CSS3. Pour se faire, plusieurs étapes sont nécessaires :

- Étape 1 : La boîte vide

Tout d’abord, nous créons une balise div standard, mais nous supprimons complètement sa taille interne. Nous définissons la largeur et la hauteur à 0. À ce stade, la boîte est invisible.

- Étape 2 : Les bordures épaisses

Ensuite, nous ajoutons une bordure épaisse aux quatre côtés de notre boîte vide. Par exemple : `border: 120px solid`.

Comme la boîte a une largeur de 0 px, les bordures ne peuvent pas s’enrouler autour d’un élément extérieur. Elles se chevauchent donc complètement.

- Étape 3 : L’angle secret

Les bordures CSS ne sont pas coupées en ligne droite. Lorsque deux bordures se rejoignent à un angle, CSS trace une diagonale à 45 degrés entre elles.

Ainsi, sans largeur ni hauteur, ces angles à 45 degrés se rejoignent au centre, formant quatre triangles distincts pointant vers l’intérieur.

## Démonstration

Lien vers le projet : https://aperbet56.github.io/triangles_en_css_pur/

## Projet développé avec

- Utilisation des balises sémantiques HTML5
- CSS3
- Flexbox
- Commentaires HTML
- Commentaires CSS
- Desktop first
- Page web responsive
