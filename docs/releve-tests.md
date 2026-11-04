# Relevé des tests

> Écrivez le résultat attendu avant d'essayer. Un écart n'est pas une faute : notez-le, corrigez, refaites le test.

**Calculs à la main** : refaites à la main les résultats de référence de `SUJET.md`, puis comparez avec votre programme. ✏️

**Essais dans le menu** : un ajout valide (encore là après redémarrage), chaque règle refusée, une recherche introuvable, chaque tri, la synthèse, un choix inconnu.

| Action | Attendu | Obtenu | Testeur |
| --- | --- | --- | --- |
| calcul a la main de la temperature moyenne : (280/10)| 28 °C|28 °C|KOFFI Axelle |
| calcul à la main dela temperature minimale |26 °C |26 °C |KOFFI Axelle |
| calcul à la main de la temperature maximale |30°C |30°C  |KOFFI Axelle |
| calcul à la main du cumul de pluie  |45 mm |45 mm |KOFFI Axelle |
| calcul à la main de journee >= 10 mm |2 journées ( M03,M08) | (M03,M08) à la main |KOFFI Axelle |

**Sur un autre poste** (`git clone`, `node app.js`, `npm test`, en suivant le README) : node app.js;npm test
