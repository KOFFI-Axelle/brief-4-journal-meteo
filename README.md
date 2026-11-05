# Journal météorologique de la ferme

> Projet individuel du SAS DFS, brief 4 (sujet : [SUJET.md](SUJET.md)). Remplacez chaque ✏️ par votre texte, puis supprimez cette ligne.

## Contexte
Cet outil sert à un agriculteur ou un technicien de ferme qui veut garder un journal météo simple : température , pluie et humidité de l air , jour par jour .Il évite de noter les relevés à la main et permet de les retrouver , de les trier et d'en tirer une synthèse.Il ne permet pas de conclure sur le climat de la région , car il ne contient que dix relevés fictifs


## Prérequis et lancement

- Node.js 20 ou plus récent, Git ; aucune bibliothèque à installer.

```bash
git clone https://github.com/VOTRE-COMPTE/brief-4-journal-meteo.git
cd brief-4-journal-meteo
node app.js
npm test
```

Sous PowerShell, si `npm` est bloqué : `npm.cmd test`.

## Fonctionnalités

- [x] Données lues et enregistrées dans `donnees/releves.json`
- [x] Ajouter un relevé, saisies invalides refusées sans arrêter le programme
- [x] Lister les relevés, message si le journal est vide
- [x] Rechercher par identifiant ou par date ; journées pluvieuses (au moins 10 mm)
- [x] Trier par température ou par pluie
- [x] Synthèse : température moyenne, minimale et maximale de la série, cumul de pluie, journées pluvieuses
- [x] Bonus : supprimer et modifier un relevé (choix 6 et 7)
- [x] Bonus : tri par température décroissante, journée la plus chaude

## Données

les 10 relevés fictifs de départ sont dans le fichier donnees/releves.json , chaque releve fournit 5 champs :id (Identifiant unique),une date,la temperatureC en °C ,la quantite de pluieMm en mm et le taux humiditeAirPct en % ,docs/dictionnaire-donnees.md

## Limites

 .Une température par jour : les températures minimale et maximale calculées sont celles de la série, pas celles de chaque .journée.
 .L'humidité relative de l'air n'est pas l'humidité du sol. 
 .Dix jours forment une courte série : le climat se caractérise sur une longue période, en général 30 ans (les normales climatiques). 
 .Le seuil de 10 mm est une catégorie d'exercice : il ne prévoit ni inondation ni stress hydrique.

## Documents

[Dictionnaire des données](docs/dictionnaire-donnees.md) · [Tâches](docs/taches.md) · [Relevé des tests](docs/releve-tests.md) · [Journal de recherche](docs/journal-recherche.md) · [Fiche agronomique](docs/fiche-agronomique.md) · [Fiche individuelle](docs/fiche-individuelle.md)

## Auteur

*Amenan Marie Axelle,KOFFI. https://github.com/KOFFI-Axelle/brief-4-journal-meteo. KANGA jules Christ au niveau des données README   *
