# GTA MOD : waypoint_position

Affiche les coordonnées (x, y) du repère placé sur la carte.

## Démo

<video controls src="waypoint_position.mp4" title="Démo du mod waypoint_position"></video>

## Fonctionnalités

- Affiche en bas à droite de l'écran les coordonnées du repère placé sur la carte, au format `Waypoint: X ... | Y ...`
- Écrit aussi les coordonnées dans la console F8 à chaque fois que le repère est posé ou déplacé

## Prérequis

- Serveur FiveM à jour avec accès admin

## Installation

1. Télécharge ce dépôt et renomme le dossier `gtamod-waypoint-position` en `waypoint_position`
2. Copie le dossier `waypoint_position` dans `resources/`
3. Ajoute `ensure waypoint_position` dans ton `server.cfg`
4. Redémarre le serveur

## Utilisation

Place un repère sur la carte (clic droit en mode carte) : ses coordonnées (x, y) s'affichent en bas à droite de l'écran, mises à jour automatiquement s'il est déplacé. L'affichage disparaît quand le repère est retiré.

## Structure du dossier

```
waypoint_position/
├─ client.lua               -- script principal
├─ fxmanifest.lua
├─ waypoint_position.mp4    -- vidéo de la démo
└─ README.md
```

## Crédits

Tuto et mod réalisés par :
Alice MASSART, PAD EMD 2026.
