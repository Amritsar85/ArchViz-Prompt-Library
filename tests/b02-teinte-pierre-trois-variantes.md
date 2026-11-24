# B02 — Teinte de la pierre claire

Comparaison rétrospective du rendu Lot_B_P1_V2(2).jpg avec les sorties A (B02 seul), B (B02 + végétation) et C (B02 + profondeur). Aucun de ces trois prompts ne contient l’ajout C02 spécifique à la teinte de la pierre.

Images converties en RGB et ramenées à 2048 × 985 avec Pillow resize par défaut. Trois rectangles sur les bandeaux du bâtiment de droite, coordonnées gauche, haut, droite, bas. Conservation des pixels où min(R,G,B)>130 et max(R,G,B)−min(R,G,B)<85. Médiane de R−B sur ces pixels (échelle 8 bits). Indicateur de dominante chaude ; il ne mesure ni la teinte jaune seule ni un écart colorimétrique perceptuel. Entre 70 % et 100 % des pixels sont retenus selon le rectangle et la sortie. Absence de recalage fin et une seule génération par condition.

| Zone | Original | A | B | C |
|---|---:|---:|---:|---:|
| Haut (1370,359,1465,382) | 19 | 40 | 37 | 31 |
| Milieu (1400,563,1500,589) | 18 | 43 | 39 | 30 |
| Bas (1110,642,1195,666) | 18 | 41 | 39 | 28 |

Les trois sorties réchauffent les trois zones. La source a déjà une légère chaleur. Prendre sa teinte comme cible. C est la plus proche parmi ces tirages ; le bénéfice ne peut pas être attribué à la consigne de profondeur. Le contrôle C02 propre à cette pierre doit être jugé séparément. Ne pas imposer une couleur de pierre universelle au preset architectural.
