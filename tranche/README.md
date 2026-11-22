# Tranche

**Tu hésites ? On tranche.** Un petit site pour t’aider à prendre une décision : le resto du soir comme les choix qui comptent vraiment.

Le site : https://tartaleb.github.io/tranche/

## Ce qu’il propose

Tu écris ta question et tes options une seule fois, puis tu peux les passer dans toutes les méthodes. Un petit guide te conseille la plus adaptée.

**Laisser faire le hasard**

- **Pile ou face** : lance la pièce et observe ta première réaction. Soulagement ou déception, elle révèle souvent ce que tu veux vraiment.
- **La roue** : toutes tes options sur une roue, avec un mode élimination.

**Prendre le temps d’y réfléchir**

- **Pour et contre** : chaque argument a un poids, la balance penche toute seule (la méthode de Benjamin Franklin).
- **Critères** : tu notes tes options sur ce qui compte pour toi (prix, plaisir, temps…), le calcul donne un score sur 100.
- **Duel** : tes options s’affrontent deux par deux, le classement se fait seul.
- **10 / 10 / 10** : comment te sentiras-tu dans 10 minutes, 10 mois et 10 ans ?
- **Les bonnes questions** : huit questions de recul (conseil à un ami, regrets, pire scénario…).

Le bouton **Tout effacer**, en haut de l’accueil, remet tout à zéro. Dans une méthode, **Effacer** ne vide que cette méthode. Les deux peuvent être annulés pendant quelques secondes.

## Sur ton téléphone

Ouvre le site, puis :

- **Android (Chrome)** : menu ⋮, puis « Ajouter à l’écran d’accueil » ou « Installer l’application ».
- **iPhone (Safari)** : bouton Partager, puis « Sur l’écran d’accueil ».

Tranche s’ouvre alors comme une appli et fonctionne aussi sans connexion.

## Tes données

Tout reste dans ton navigateur. Rien n’est envoyé nulle part, il n’y a ni compte ni pistage.

## Le projet

| Fichier | Rôle |
| --- | --- |
| `index.html` | Toute l’application : page, styles et code |
| `sw.js` | Fonctionnement hors connexion |
| `manifest.webmanifest`, `icons/` | Installation sur l’écran d’accueil |
| `fonts/` | Police Archivo (licence SIL Open Font License, voir `fonts/OFL.txt`) |

Aucune étape de compilation : c’est un site statique, publié tel quel avec GitHub Pages.
