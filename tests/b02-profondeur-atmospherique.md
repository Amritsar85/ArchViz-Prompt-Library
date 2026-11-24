# B02 — Profondeur atmosphérique

Variante C depuis la source Lot_B_P1_V2(2).jpg et le texte B02, avec cet ajout :

> Match the source image's atmospheric perspective at each distance. Preserve the pale, low-contrast silhouettes of the distant pines on the right and the distant buildings on the left. Match their original tonal range, saturation and visibility through the existing daylight haze. Keep foreground and main-subject detail at the source level. Do not dehaze, sharpen distant silhouettes or add lens blur.

Écart-type des niveaux de gris PIL L sur des rectangles proportionnels au format source (2048 × 985), coordonnées gauche, haut, droite, bas. Comparaison indicative, sans recalage géométrique ni graine commune.

| Zone | Source | B02 seul | B02 + végétation | B02 + profondeur ciblée |
|---|---:|---:|---:|---:|
| Pins (1680,475,1810,615) | 26,8 | 59,3 | 58,7 | 27,6 |
| Bâti lointain (10,500,200,610) | 29,9 | 56,0 | 56,2 | 30,7 |
| Façade principale (1000,450,1170,590) | 72,1 | 66,2 | 67,2 | 65,7 |

La variante C rapproche le contraste du fond de la source sur cette scène. La façade reste moins contrastée. Un essai par variante, à confirmer sur une seconde scène avant généralisation.
