# Carrousel Maker

Outil de composition de carrousels Instagram pour l'évaluation journalistique.

Carrousel Maker permet de créer rapidement des carrousels Instagram structurés à partir d'un sujet d'actualité. L'outil guide la composition en imposant une structure éditoriale précise et des limites de caractères pour chaque slide.

## Utilisation

Ouvrez l'URL suivante dans **Chrome** ou **Edge** (Safari non supporté) :

👉 **https://davanac.github.io/carousel-maker**

Aucune installation requise — l'outil fonctionne entièrement dans le navigateur.

## Structure des slides

| Slide | Rôle | Champs | Limite |
|-------|------|--------|--------|
| 1 | **Accroche** | Thématique | 30 caractères |
| | | Titre | 150 caractères |
| | | Sous-titre | 250 caractères |
| 2 | **Le Chiffre** | Chiffre | 20 caractères |
| 3 | **Explication** | Texte | 350 caractères |
| 4 | **Citation** | Citation | 200 caractères |
| | | Auteur | 60 caractères |
| | | Description source | 100 caractères |

- La **Slide 1 (Accroche)** reste toujours en première position.
- Les slides 2, 3 et 4 peuvent être **réordonnées** librement via les boutons ▲ / ▼.
- Des **slides Explication supplémentaires** peuvent être ajoutées (et supprimées).
- Les données sont **sauvegardées automatiquement** dans le navigateur (localStorage) : un rafraîchissement accidentel ne fait pas perdre le travail en cours.

## Tech

- HTML / CSS / JavaScript autonome — **aucune dépendance externe**
- Rendu via l'API Canvas
- Export JPEG 1080 × 1350 px (format Instagram portrait)
- Sauvegarde automatique via localStorage (textes, images, ordre des slides)

## Licence

MIT
