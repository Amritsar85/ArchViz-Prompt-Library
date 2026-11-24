# ArchViz Atelier — socle d’audit du 24 novembre 2026

## Référence technique

Site 1.1.6, révision du site auditée `cd1f10a`. Bibliothèque de référence sur main à la révision `f28432fe673e2afd055fd22a444866de033fa746`. Les six configurations B01 à B06 proviennent de l’archive du 4 novembre, préparée sur une version antérieure du site (`0fca20b`).

Sur 71 entrées embarquées, 69 sources correspondent octet par octet aux fichiers sur main. Les deux autres recettes, homogénéisation et rééclairage, sont sauvegardées sur la branche de la PR 4. Les 27 fichiers de consignes hors catalogue dédié se répartissent entre recherche de concept (9), retouche (6), insertion (6) et expérimental (6). Ces chiffres décrivent le référencement par fichier. Certaines fonctions sont aussi couvertes par des recettes complètes.

## Composition vérifiable des recettes

Comparaison du corps de chaque recette publiée avec le texte intégral de chaque brique du catalogue. Une correspondance indique que le passage est présent mot pour mot. Une recette peut aussi contenir du texte autonome ou reformulé. La table ne prouve ni l’intention de l’auteur ni l’ordre d’assemblage historique.

| Recette | Briques retrouvées intégralement |
|---|---|
| architecture-precise | locks/architecture, locks/camera, modules/architecture, modules/materials, modules/sharpness |
| concept-massing-exploration | Aucune correspondance exacte |
| context-aware-person-insertion | Aucune correspondance exacte |
| daylight-harbor-preservation | locks/geometry/maximum-preservation, masters/universal-short |
| daylight-housing-preservation | locks/components-detailed, locks/geometry/maximum-preservation, locks/site-circulation, locks/source-daylight, masters/universal-short, modules/materials-fine-render |
| marina | locks/architecture, modules/marina, modules/people, modules/sharpness, modules/water |
| object-integration | locks/architecture, locks/camera, locks/landscape, modules/local-object |
| photographic-atmosphere | locks/camera, modules/camera, modules/lighting, modules/materials |
| photorealism-short-preservation | locks/geometry/maximum-preservation, masters/universal-short |
| residential | locks/architecture, modules/lighting, modules/materials, modules/vegetation |
| urban | locks/camera, modules/materials, modules/people, modules/sharpness |
| vegetation-sharpness | locks/architecture, locks/vegetation, modules/sharpness, modules/vegetation-sharpness |
| existing-photo-daylight-relighting | Aucune correspondance exacte |
| photomontage-homogenization | Aucune correspondance exacte |

## Références visuelles

| Scène | Repère de comparaison | Décision à ce stade |
|---|---|---|
| B01, balcons courbes | Courbure des dalles, chemin vers le banc, feuillage devant les garde-corps | Géométrie générale lisible. Contrôler les occultations par la végétation. |
| B02, pierre en lumière dorée | Couleur de la pierre à l’ombre et sur les arêtes éclairées | Privilégier les accents chauds localisés. |
| B03, tour en contre-plongée | Maille du balcon d’angle au-dessus du cyprès et panneau du niveau inférieur | La consigne sur le remplissage aide sur le premier balcon. Transparence variable sur le second. Variante candidate. |
| B04, intérieur | Cinq personnes, mobilier, trame vitrée, direction des lames et ombres au sol | Variante courte candidate. La lumière sur le bois et le reflet du jardin dérivent encore. |
| B05, vue aérienne | Comparer les arbres du parking et du premier plan à la source | V1 préférée pour le contraste. La source reste la référence des nuances de vert. |
| B06, insertion de rue | Vitrines, pied de façade, arbre derrière la grange, ciel et famille | Première insertion retenue pour le raccord. Évaluer séparément la fidélité du contexte photographique. |

## Vérifications avant une évolution

1. Conserver le texte de la recette de référence. Enregistrer séparément le changement proposé, la source, le modèle et les dimensions d’entrée et de sortie.
2. Comparer les mêmes détails à la même échelle et répéter les essais avant de proposer une nouvelle valeur par défaut. Un résultat préféré sur une scène reste une préférence locale.
3. Pour une recette personnalisée, présenter le texte de référence, les ajouts et les remplacements dans leur ordre réel. Pour un texte autonome, l’indiquer explicitement.
4. Rejouer les six suites fonctionnelles, puis vérifier dans le navigateur les deux destinations avec un repère différent en fin de prompt. Lors du contrôle du site publié, les deux copies étaient intégrales et les deux services se sont ouverts.
5. Pour une synchronisation, comparer les chemins et empreintes à la révision précédente, signaler les suppressions et examiner les entrées propres au site avant remplacement. Présenter les changements en prévisualisation.

Les essais visuels établissent une première référence pour la comparaison. La répétabilité sur d’autres modèles et la conservation des détails à la définition de production restent à mesurer.
