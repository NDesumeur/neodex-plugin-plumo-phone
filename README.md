# Plumo

Un jeu d'adresse à une touche : fais voler un petit oiseau entre des colonnes de pierre. Il retombe tout seul, chaque battement d'ailes le fait remonter. Passe le plus de colonnes possible et gagne des médailles.

*English version: [README.en.md](README.en.md)*

## Version téléphone

On joue d'un doigt : chaque toucher de l'écran fait battre des ailes. Les boutons NOUVELLE PARTIE, PAUSE et PLEIN ÉCRAN sont juste sous le jeu, et la partie se met en pause toute seule quand tu quittes l'appli (un appel, l'écran qui s'éteint). Le jeu prend toute la largeur du téléphone ; records, médailles, oiseaux et mondes sont en dessous.

## Mondes, oiseaux et médailles (nouveau en 1.2.0)

- Quatre **mondes**, chacun avec son record : **Prairie** ; **Forêt** (des lucioles entre les troncs, +1 point chacune) ; **Ville** (les immeubles montent et descendent dès 10 points) ; **Neige** (le vent souffle dès le début, la neige tombe). Chacun a son ciel de jour et de nuit.
- Chaque **oiseau** vole à sa façon : Plumo équilibré, **Rougegorge** léger (tombe doucement, le vent le pousse), **Mésange** petite (passe plus facilement), **Flamant** lourd (grands battements, le vent le pousse peu), **Phénix** qui renaît une fois par partie.
- Une **médaille s'annonce en jeu** dès qu'un palier est passé : bronze (10), argent (25), or (50), platine (100) et la nouvelle **diamant** (150).

## Commandes

- **Clic**, **Espace**, **↑** ou **Entrée** : un battement d'ailes, qui donne une impulsion vers le haut.
- **P** : pause ; un clic reprend.
- Après une chute, un clic relance une partie.

## Règles

- L'oiseau tombe sans arrêt : il faut battre des ailes au bon rythme pour passer dans l'ouverture de chaque colonne.
- Toucher une colonne ou le sol termine la partie.
- Chaque colonne passée vaut 1 point.
- Les ouvertures se resserrent petit à petit (d'environ un tiers au bout d'une quarantaine de points) et l'oiseau va de plus en plus vite, jusqu'à plus de moitié plus vite à 60 points.

## Le ciel

Le décor change tous les 25 points : jour, soir, nuit étoilée puis aube, et le cycle recommence.

## Médailles

À la fin de chaque partie, une médaille selon ton score : **bronze** à 10 points, **argent** à 25, **or** à 50, **platine** à 100. Le panneau des médailles compte combien tu en as gagné de chaque sorte.

## Après 50 points

- Certaines **colonnes bougent** de haut en bas (deux petits traits blancs les signalent).
- Des **rafales de vent** soufflent de temps en temps : « RAFALE » s'affiche en jaune une seconde avant, puis le vent pousse l'oiseau vers le haut (↑) ou vers le bas (↓) pendant deux à trois secondes.

## Oiseaux

Chaque médaille gagnée au moins une fois débloque un oiseau : **Rougegorge** (bronze), **Mésange** (argent), **Flamant** (or) et **Phénix** (platine, avec sa traîne de feu). On le choisit dans la case **Oiseaux** ; **Plumo** reste disponible.

## Manette et plein écran

À la manette : **A**, **B**, la croix ou le stick vers le haut pour battre des ailes, **Start** pour la pause. Le bouton **Plein écran** agrandit le ciel à tout l'écran (Échap pour en sortir) ; hors plein écran, le jeu prend toute la hauteur de la fenêtre.

## Statistiques

Meilleur score, nombre de parties et battements d'ailes au total.

## Données et synchronisation

Ton record, tes médailles et tes statistiques sont enregistrés par NeoDex, sauvegardés et synchronisés entre tes PC si la synchro est activée.

## Installer

Dans NeoDex : **NeoStore → À découvrir → Plumo → Installer**.

Développer un plugin : voir le [SDK NeoDex](https://github.com/NDesumeur/neodex-sdk).
