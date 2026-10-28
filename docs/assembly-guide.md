# Guide d'assemblage

Copier le **corps** du prompt maître, puis le corps des modules et verrous choisis. Les titres de fichier servent au classement.

- Marina : `MASTER_01 + WATER_01 + MARINA_01 + PEOPLE_01 + SHARPNESS_01 + LOCK_ARCHITECTURE`.
- Résidence/jardin : `MASTER_01 + MATERIALS_01 + VEGETATION_01 + LIGHTING_01 + LOCK_ARCHITECTURE`.
- Vue urbaine : `MASTER_01 + MATERIALS_01 + PEOPLE_01 + SHARPNESS_01 + LOCK_CAMERA`.
- Architecture précise : `MASTER_01 + ARCHITECTURE_01 + MATERIALS_01 + SHARPNESS_01 + LOCK_ARCHITECTURE + LOCK_CAMERA`.
- Végétation floue : `MASTER_02 + VEGETATION_02 + SHARPNESS_01 + LOCK_ARCHITECTURE + LOCK_VEGETATION`.
- Ambiance photo : `MASTER_01 + LIGHTING_01 + CAMERA_01 + MATERIALS_01 + LOCK_CAMERA`.
- Ajout d'objets : `LOCAL_02 + LOCK_ARCHITECTURE + LOCK_CAMERA + LOCK_LANDSCAPE`.

Ne pas empiler tous les blocs systématiquement : un grand nombre de consignes répétées peut entraîner des arbitrages inattendus. En particulier, ne pas utiliser `LOCK_OBJECTS` en même temps qu'une demande de remplacement des bateaux, sans exception explicite.
