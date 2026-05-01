# FORGE — Suivi Musculation

PWA premium pour le suivi de musculation, pensée pour fonctionner **offline** en salle de sport.

## Fonctionnalités

- **Accueil** — vue d'ensemble : objectif, progression, stats globales, dernière séance
- **Séances** — créer une séance, ajouter des exercices, noter reps × poids série par série
- **Poids** — pesées avec courbe d'évolution et ligne d'objectif
- **Exos** — bibliothèque de 20 mouvements classés par groupe musculaire
- **Profil** — informations personnelles et objectif

## Stack

- HTML / CSS / JavaScript — un seul fichier
- `localStorage` pour la persistance des données
- Pas de dépendance externe (sauf Google Fonts)
- Pas de framework, pas de build

## Installation sur iPhone

1. Ouvrir l'URL dans **Safari**
2. Bouton Partager → **Sur l'écran d'accueil**
3. L'app fonctionne désormais **sans connexion internet**

## Déploiement GitHub Pages

1. Push ce repo sur GitHub
2. Settings → Pages → Source : `main` / `(root)` → Save
3. Accéder à `https://<user>.github.io/<repo>/`

## Données

Tout est stocké localement sur l'appareil (`localStorage`).
Bouton « Exporter mes données » dans l'onglet Profil pour faire un backup JSON.
