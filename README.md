# Medivision AI Pro — base PWA expérimentale

**Catégorie : prototype web / HealthTech** · Studio Niko Design

> **État actuel du dépôt :** cette branche contient essentiellement le **starter PWABuilder** (Lit, TypeScript, Vite, Workbox et Shoelace). Les fichiers `package.json` et `src/pages/app-home.ts` portent encore des identifiants et textes de démonstration du modèle initial. Il serait donc trompeur de présenter cette base comme une application médicale prête à l'emploi.

Pour le prototype documenté d'imagerie médicale de Studio Niko Design, voir le dépôt séparé **[medicalvisionproai](https://github.com/Nikoju1977/medicalvisionproai)**.

## Démarrer

Prérequis : Node.js et npm compatibles avec les dépendances du projet.

```bash
npm ci
npm run dev
```

L'URL locale est indiquée par Vite dans le terminal.

## Vérifier et construire

```bash
npm run build
```

Le script exécute TypeScript (`tsc`) puis Vite. Cette documentation ne prétend pas que la compilation, les tests ou l'installation PWA ont été validés ici.

## Structure

| Chemin | Rôle |
| --- | --- |
| `src/app-index.ts` | Composant racine Lit |
| `src/pages/app-home.ts` | Page d'accueil du starter |
| `src/components/` | Composants d'interface |
| `public/` | Ressources statiques |
| `vite.config.ts` | Configuration Vite |
| `swa-cli.config.json` | Configuration Azure Static Web Apps |

## Avant de publier une application médicale

- Remplacer le contenu de démonstration et choisir un nom de package spécifique.
- Définir le périmètre médical et les usages explicitement **exclus**.
- Vérifier les licences des composants réutilisés.
- Ajouter des tests techniques, une politique de confidentialité adaptée et une revue de sécurité.
- Ne jamais utiliser de données de patients réels dans une démonstration publique sans cadre approprié.

Ce dépôt ne revendique aucune validation clinique ni conformité réglementaire.

## Crédits

Base dérivée du [PWABuilder PWA Starter](https://github.com/pwa-builder/pwa-starter). Consulter sa documentation et les licences de ses dépendances.

[Catalogue Studio Niko Design](https://github.com/Nikoju1977).
