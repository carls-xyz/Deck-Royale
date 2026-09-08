# Deck Royale

Projet de groupe autour du jeu Clash Royale : constitution de decks et organisation de tournois, avec les données récupérées depuis l'API officielle Supercell.

Projet académique réalisé à l'IIM en mars 2026, avec [@AilesVax](https://github.com/AilesVax) et [@maximilien-ilic](https://github.com/maximilien-ilic).

## État du projet

Le projet en est resté au stade de la mise en place : application Next.js initialisée et premier appel à l'API Clash Royale (`clash-royal/serv/lien.tsx`, page `clash-royal/app/clash`). Les fonctionnalités de création de decks et de gestion de tournois n'ont pas été développées.

## Stack

- **Next.js** avec l'App Router et **TypeScript**
- **Tailwind CSS**
- **API Clash Royale** de Supercell

## Lancer le projet

```bash
cd clash-royal
npm install

# L'API Clash Royale exige un jeton lié à une adresse IP,
# à créer sur developer.clashroyale.com
npm run dev
```

<!--
Charles : si tu as travaillé sur une partie précise de ce projet, ajoute ici une
section "Ma contribution" en le disant. L'historique Git de ce dépôt ne contient
aucun commit à ton nom, donc mieux vaut le préciser toi-même plutôt que laisser
un doute.
-->
