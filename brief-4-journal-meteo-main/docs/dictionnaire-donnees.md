# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | Exemple |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, absent des données | — | M06|
| `date` |date du releve |nombre |AAAA-MM-JJ |- |2026-10-20 |
| `temperatureC` |Température |nombre|négatif ou décimal possible  |°C | 30|
| `pluieMm` |Pluie |nombre |positif ou nul  | mm |0 | 
| `humiditeAirPact` |Humidité relative de l'air | nombre|un nombre entre 0 et 100 |% |68 |

**Listes de valeurs autorisées** :temperatureC = négatif ou décimal possible
                                   pluieMm = positif ou nul
                                humiditeAirPact = un nombre entre 0 et 100

**Sources** : SUJET.md , releves.json
