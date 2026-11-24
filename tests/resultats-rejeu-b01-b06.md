# Rejeu des assemblages du 24 novembre 2026

Référence : archive du 4 novembre, commit de site indiqué par son manifeste `0fca20b849672631f26d09c0562cc82ae94a0d2e`.

Le test charge les scripts du site et appelle buildPrompt avec chacune des six configurations du manifeste. La chaîne produite est comparée directement au fichier texte archivé, espaces et fins de ligne compris. Son SHA-256 est ensuite comparé à celui du manifeste.

| Cas | Texte | SHA-256 |
|---|---|---|
| B01 | Identique | `64b7d032cdd050983233cf01d87ac7080c18545faaf310f62551cbdb278ed5c8` |
| B02 | Identique | `fc76769acfa62e63d0f000923599d52ee1501d49047976fc08fa9c8cfd5f1c97` |
| B03 | Identique | `fc76769acfa62e63d0f000923599d52ee1501d49047976fc08fa9c8cfd5f1c97` |
| B04 | Identique | `b544f44afc6a01ba2d1ac7447f23d606a86b01d8dbbaab038bb6bdacdfb1df58` |
| B05 | Identique | `0c1e3ad956a5d808e54564641c5d3656e9a57e50ff995dfd9d11b492ad9103df` |
| B06 | Identique | `fe8a31d6cff4f677cd6009ced3cdc0e6bfcc18c35b183160f16533b2ddc1e464` |

B02 et B03 produisent le même texte. Ces six cas couvrent les configurations archivées. La génération d’images, la stabilité entre modèles et les combinaisons hors de ce lot appellent des évaluations distinctes.
