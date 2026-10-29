# ArchViz Prompt Library

Bibliothèque **gratuite et publique** de prompts modulaires (en anglais) pour la photoréalisation de rendus architecturaux dans Gemini / Nano Banana et autres outils d'édition d'images.

## Utilisation

1. Ouvrir ce dossier dans VS Code (`Fichier > Ouvrir un dossier`).
2. Choisir `masters/universal-long.md` ou `masters/universal-short.md`.
3. Ajouter uniquement les modules pertinents dans `modules/`.
4. Ajouter un verrou dans `locks/` si nécessaire.
5. Pour commencer rapidement, copier un prompt déjà assemblé dans `presets/`.
6. Importer le rendu original dans l'outil et coller le texte du prompt. Vérifier la géométrie après génération.

Les modèles génératifs ne garantissent pas la conservation des pixels, proportions ou détails architecturaux, même avec un verrou textuel. Pour les corrections critiques, utiliser des masques Photoshop/Krita.

## Organisation
- `masters/` : prompts de base.
- `modules/` : blocs spécialisés.
- `locks/` : contraintes de préservation.
- `presets/` : prompts complets déjà assemblés et prêts à copier.
- `examples/marina/` : fiche de test, sans image du projet par défaut.
- `docs/` : méthode et conseils de versionnement.

## Réglages de départ
Pour des essais : Nano Banana 2.1, 2K, aspect ratio Auto, thinking selon les options et le coût affichés. Agrandir ensuite dans Photoshop si le résultat le justifie. Ce sont des préférences de workflow, pas des garanties de qualité.

## Confidentialité
Ne pas publier de rendus d'agence ou de client sans autorisation. Le dépôt est destiné à être **public et gratuit**. Conserver les essais clients et documents confidentiels dans un espace privé séparé. Ne jamais commiter de clé API, d'identifiants ou de données de facturation.

## Modules avancés (V1 enrichie)
- `ambiences/` : heure de la journée, météo, saisons et ambiance.
- `locks/geometry/` : protection renforcée des volumes, perspectives et détails constructifs.
- `editing/` : ajout, suppression, remplacement ou retouche localisée.
- `tests/` : fiche de comparaison reproductible.
- `docs/priority-rules.md` : règles de compatibilité et priorité.
- `docs/release-checklist.md` : vérifications avant publication.

## Licences et publication
La bibliothèque de prompts et sa documentation originale sont publiées sous [CC BY 4.0](LICENSE.md). L'utilisation de certains modèles d'IA peut être payante. Les images de clients ou d'employeurs ne sont **pas** comprises dans cette licence.

## Concept research & context-aware insertion (V1.1)
- `concept-design/` : recherche de formes, façades, matériaux, espaces et variantes conceptuelles. **Autorise** des transformations selon le niveau de liberté choisi.
- `insertion/` : ajout d'objets guidé par les références déjà présentes à la même profondeur, ou par un proxy 3D.
- `presets/concept-massing-exploration.md` et `presets/context-aware-person-insertion.md` : exemples assemblés.
- `docs/modes-and-priorities.md` : éviter de mélanger les consignes de photoréalisation stricte et d'exploration libre.

Les propositions conceptuelles sont des supports de recherche visuelle, non des projets techniques validés.

## Politique des matériaux (V1.2)
Par défaut, les matériaux architecturaux sont **propres et entretenus** : la photoréalisation n’implique pas de salir les enduits.
- `modules/materials-clean-facades.md` : renforce la propreté des façades et enduits.
- `modules/material-weathering-optional.md` : salissures, patine et vieillissement **uniquement sur demande explicite**.
Les prompts maîtres et presets de photoréalisme ont été harmonisés avec cette règle.

## Banc d’essai T01-T08 (29 octobre 2026)

- [Bilan des huit essais](tests/2026-10-29-t01-t08.md) : deux vues du même environnement, préférences esthétiques et limites de fidélité.
- [Recette courte retenue (T02)](presets/photorealism-short-preservation.md) : assemblage du maître court et du verrou géométrique, sans modifier leurs textes.
- [Blocs expérimentaux](experimental/README.md) : chaleur, brume, textures, ID pass et priorités de fidélité ; pas de validation générale.
- [Postproduction hybride](docs/hybrid-postproduction.md) : comparaison, recalage et restauration de l’original par masques.

T02 est une référence esthétique, pas une garantie de conformité. Les consignes 4K / Auto / Medium de cette série sont distinguées des dimensions réelles des fichiers reçus. Les images de projet et le rapport illustré restent hors du dépôt public.
