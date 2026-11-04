# Dictionnaire des données

> Un champ par ligne, d'après `SUJET.md` et le fichier de `donnees/`. La première ligne sert de modèle.

| Champ | Signification | Type | Règle de validation | Unité | M10 |
| --- | --- | --- | --- | --- | --- |
| `id` | Identifiant unique | texte | non vide, unique | — |M10 |
| `date` |date du releve |Texte |AAAA-MM-JJ |- |2026-10-24  |
| `temperatureC` |Température |nombre |un nombre, négatif ou décimal possible |°C  |30 |
| `pluieMm` |pluie |nombre |un nombre positif ou nul |mm |2 |
|`humiditeAirPct`  |humidite relative de l ' air  |nombre|un nombre entre 0 et 100 |% |74 |

**Listes de valeurs autorisées** :  -id (non vide, unique)
                                    -date (format AAAA-MM-JJ)
                                    -temperatureC (un nombre,négatif ou décimal possible )
                                    -pluieMm (un nombre positif ou nul)
                                    -humiditeAirPct(un nombre entre 0 et 100 )
**Sources** : SUJET.md,données/releves.json
