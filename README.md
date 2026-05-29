# 影 Shen Varath — Fiche de personnage D&D 5e

Fiche de personnage interactive pour **Shen Varath**, Moine niveau 3, Voie de l'Ombre, Shadar-Kaï.

Inspirée du projet [Torvin "Trois-Parchemins"](https://github.com/Funkyst4rz/torvin).

---

## ✨ Fonctionnalités

- **5 onglets** : Stats · Combat · Ki & Capacités · Histoire · Dés
- **Tracker PV** interactif avec barre de vie en en-tête
- **Tracker Ki** — 3 points cliquables (dépenser / récupérer)
- **Conditions de combat** cliquables
- **Jets de mort** interactifs
- **Repos court / long** — restaure PV et Ki automatiquement
- **Lanceur de dés** — d4, d6, d8, d10, d12, d20, d%
- **50 Sentences de Shen** — proverbes absurdes style Kaamelott
- **Sauvegarde locale** (localStorage) — PV et Ki persistent entre les sessions
- Design sombre thématique · Optimisé mobile (iPhone)

---

## 🚀 Déployer sur GitHub Pages

### Méthode 1 — Fork (recommandée)

1. **Fork** ce repository
2. Aller dans **Settings → Pages**
3. Source : `Deploy from a branch`, branche `main`, dossier `/`
4. Cliquer **Save**
5. Accéder à : `https://[votre-username].github.io/shen-varath/`

### Méthode 2 — Nouveau repository

1. Créer un nouveau repository (ex: `shen-varath`)
2. Uploader `index.html` à la racine
3. Activer GitHub Pages (voir Méthode 1, étape 2-4)

---

## 📁 Structure

```
shen-varath/
├── index.html    ← Application complète (HTML + CSS + JS)
└── README.md     ← Ce fichier
```

Tout est dans un seul fichier `index.html` — pas de dépendances locales, pas de build requis. Google Fonts est chargé depuis CDN.

---

## 🎲 Personnage

| Attribut | Valeur |
|----------|--------|
| Nom | Shen Varath |
| Race | Shadar-Kaï (Elfe des ombres) |
| Classe | Moine niveau 3 — Voie de l'Ombre |
| Historique | Ermite |
| Alignement | Loyal Neutre |
| PV | 22 · CA 17 · Initiative +4 · Vitesse 40 ft |
| Ki | 3 points · DD 14 |
| Langues | Commun · Elvish · Sylvain |

---

## 🔮 Mise à jour future

Pour passer au **niveau 4** : modifier dans `index.html` les valeurs statiques (PV max, Ki max, caractéristiques si ASI) et le texte de la section histoire.

---

*Créé avec Claude · Campagne D&D 5e*
