# 🏆 THE FINALS — Rank Tracker

Suivi de progression ranked pour **THE FINALS**. Saisie manuelle après chaque partie, rang calculé automatiquement à partir du RS, historique par saison, et partage direct vers Discord.

Installable comme une vraie app sur **PC, Android et iOS** (PWA — pas besoin de passer par un store).

---

## ✨ Fonctionnalités

- **Rang automatique** — calculé à partir du RS saisi (Bronze / Argent / Or / Platine / Diamant)
- **Historique par saison** — clôture une saison, l'historique des précédentes reste consultable, rien ne se mélange après un reset
- **Graphique de progression** — courbe du RS dans le temps, filtrable sur 7 jours / 30 jours / tout
- **Projection de rang** — estimation du nombre de parties avant le prochain palier, au rythme actuel
- **Édition & suppression** des entrées, détection des doublons
- **Export / import** des données en JSON
- **Partage Discord** — capture ta carte de rang et l'envoie directement via le menu de partage natif (mobile)
- **Multilingue** — Français / English / 한국어
- **Mode clair / sombre**
- **100 % local** — aucune donnée envoyée à un serveur, tout reste sur ton appareil

---

## 📲 Installation

1. Ouvre l'URL GitHub Pages du repo sur ton téléphone ou ton PC
2. **Android (Chrome)** → bandeau "Ajouter à l'écran d'accueil"
   **iOS (Safari)** → Partager → "Sur l'écran d'accueil"
   **PC (Chrome/Edge)** → icône d'installation dans la barre d'adresse
3. L'app s'ouvre ensuite comme une application indépendante, avec sa propre icône

> Chaque appareil garde ses propres données (stockage local) — pas de synchronisation entre plusieurs appareils.

---

## 🛠️ Stack

HTML / CSS / JavaScript vanilla — aucune dépendance à builder, aucun serveur. Un seul fichier `index.html` + un service worker pour le mode hors-ligne et l'installation PWA.

---

## 📄 Licence

Usage personnel — fait par [KMLAR](https://github.com/) pour suivre sa progression ranked entre potes.
