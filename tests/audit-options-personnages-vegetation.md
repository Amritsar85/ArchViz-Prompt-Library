# Personnages et végétation — 24 novembre 2026

Moteur de l’instantané du site utilisé pour le rejeu B01–B06. Pour chaque entrée, appeler buildPrompt avec les valeurs de defaults(), enabled vide, puis avec seulement people ou seulement vegetation. Utiliser recipeVariant pour les quatorze recettes nommées. Comparer le texte intégral à réglages identiques.

| Entrée | Personnages modifie le texte | Végétation modifie le texte |
|---|---|---|
| Assemblage libre et onze recettes ordinaires | Oui | Oui |
| context-aware-person-insertion | Non, protection contre l’ajout incompatible | Oui |
| existing-photo-daylight-relighting | Non, options désactivées | Non, options désactivées |
| photomontage-homogenization | Non, options désactivées | Non, options désactivées |

25 différences sur 30 comparaisons. Le test mesure l’effet textuel des options du catalogue. Certaines recettes comportent aussi des prescriptions intrinsèques.

Lecture de paint() : le résumé des recettes photo explique la désactivation. Les badges sont toutefois alimentés par state.enabled après filtrage des incompatibilités, même dans ces deux recettes. Avec des options mémorisées, ils peuvent donc suggérer des blocs supplémentaires que buildPrompt ne produit pas. Recommandation : dériver les badges de la composition effective, ou afficher une seule indication de protections intégrées pour les recettes photo.

La fidélité des visages et le détail du lierre et des pins sont des propositions en brouillon. Cette série ne mesure pas leur efficacité sur les images.
