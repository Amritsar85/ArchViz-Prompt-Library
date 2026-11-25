# Définition native — 25 novembre 2026

Lecture des dimensions avec Pillow Image.open(...).size avant redimensionnement. Neuf PNG de génération, comparés au fichier source fourni pour chaque scène. Pourcentage de pixels = 100 × surface de sortie / surface source. Écart de ratio = 100 × (ratio sortie / ratio source − 1).

```text
sortie   source_W H   sortie_W H   %pixels  %écart_ratio
e86b3262 2048 985 1808 870 77.97 -0.049
f52d116f 2048 985 1808 870 77.97 -0.049
aadf669c 2048 985 1810 869 77.97 0.176
adf40151 2048 985 1810 869 77.97 0.176
a7759337 2048 985 1808 870 77.97 -0.049
f0dad131 2048 1299 1574 999 59.11 -0.065
3ec4e79a 2048 1299 1575 999 59.14 -0.001
ef3e24ea 2048 1160 1666 944 66.2 -0.039
7b34a279 2048 1160 1666 944 66.2 -0.039
```

Les neuf fichiers contiennent environ 1,57 million de pixels chacun. Le ratio est proche de celui de la source dans chaque cas. Les dimensions natives sont inférieures pour les neuf sorties. Ces mesures ne quantifient ni le déplacement des contours ni la fidélité des détails. Pour les comparaisons ultérieures, consigner dimensions natives et dimensions utilisées pour la lecture. Un redimensionnement de contrôle ne constitue pas une restauration des détails.
