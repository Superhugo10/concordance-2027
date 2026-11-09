# Concordance 2027

Outil d'aide au vote pour l'élection présidentielle française de 2027 : https://superhugo10.github.io/concordance-2027/

On classe les sujets qui comptent pour soi, on donne son avis sur des mesures concrètes, et l'outil calcule la proximité avec chaque candidat. Chaque position est reliée à sa source.

## Méthode

- Chaque position de candidat est codée de -2 (pas du tout d'accord) à +2 (tout à fait d'accord), avec un lien vers la source et une courte citation.
- Sources primaires uniquement : programmes, sites de campagne, documents de parti, votes à l'Assemblée et au Parlement européen, entretiens rapportés mot pour mot.
- Une position manquante n'est pas comptée. Une position « déduite » (position du parti, vote du groupe, prise de position voisine) compte pour moitié et est signalée comme telle.
- Une affirmation n'est affichée que si au moins 4 candidats ont une position sourcée. Chaque score indique sur combien de réponses il repose et son niveau de fiabilité.
- Aucune couleur de parti, aucune photo ; candidats et questions dans un ordre tiré au hasard pour chaque visiteur. L'outil ne recommande personne.
- Les réponses restent dans le navigateur du visiteur : rien n'est envoyé. Le lien « Partager mes résultats » encode les réponses dans l'adresse.

## Transparence

- L'onglet « Mises à jour » du site liste chaque position ajoutée, modifiée ou retirée, avec sa date.
- Une erreur de codage ? Utilisez le lien « Signaler une erreur » à côté de la position, ou ouvrez une *issue*, avec une source primaire.

## Fichiers

- `index.html` : le site complet, autonome (toutes les données sont incluses).
- `og.png` : image d'aperçu pour le partage du lien.

Ce site n'est affilié à aucun parti ni candidat.
