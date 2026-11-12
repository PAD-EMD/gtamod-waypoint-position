# GTA MOD : waypoint_position

Afficher les coordonées (x, y, z) du joueur.

## Démo

<video controls src="waypoint_position.mp4" title="Démo du mod waypoint_position"></video>

## Fonctionnalités

- Afficher les coordonées (x, y) en bas de l'écran du repère placée sur la carte, au format x: ... y: ...

## Prérequis

- Serveur FiveM à jour avec accès admin

## Installation

1. Télécharger le dossier `waypoint_position`
2. Copier le dossier `waypoint_position` dans `resources/`
3. Ajouter `ensure waypoint_position` dans ton `server.cfg`
4. Redémarrer le serveur

## Utilisation

Place un repère sur la carte (clic droit en mode carte) : ses coordonnées (x, y) s'affichent en bas à droite de l'écran, mises à jour automatiquement s'il est déplacé.

## Structure du dossier

```
gtamod-waypoint-position/
├─ waypoint_position/                      -- dossier du mod
│  ├─ waypoint_position.lua         -- script principal
│  └─ fxmanifest.lua
├─ waypoint_position.mp4                   -- vidéo de la démo
└─ README.md
```

## Crédits
Tuto et Mod réalisés par :
Alice MASSART, PAD EMD 2026.