# Adataviz — Femmes illustres à Paris

Site web qui affiche des portraits de femmes illustres à Paris à partir de l'API OpenData de Paris.

## 🚀 Lancer le projet

```bash
pnpm install
pnpm dev
```

Puis ouvrir [http://localhost:5173](http://localhost:5173)

## ✨ Fonctionnalités

- Affichage des données depuis l'[API OpenData Paris](https://opendata.paris.fr/)
- Barre de recherche par nom
- Bouton "Voir plus / Voir moins" pour les descriptions
- Chargement paginé via un bouton "Charger plus"
- Design responsive (1 → 2 → 3 colonnes)

## 🛠️ Stack

- Vanilla JavaScript
- CSS (custom properties, grid, flexbox, animations)
- Vite

## 📁 Structure

```
src/
├── main.js       # Logique JS (fetch, DOM, recherche)
└── style.css     # Styles globaux
```
