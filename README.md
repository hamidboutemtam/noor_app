# NOOR - Application de Motivation Islamique

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-green" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-blue" alt="License">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-orange" alt="Platform">
</p>

## 🌟 Présentation

**NOOR** est une application de motivation et d'encouragement destinée aux musulmans. Elle délivre des citations authentiques issues de la tradition islamique, adaptées à l'état émotionnel de l'utilisateur.

### Fonctionnalités

- 📖 **Citations du Coran** - Versets authentiques avec texte arabe
- 📚 **Hadiths & Rappels** - Sagesses issues des sources sahih
- 💪 **Messages d'action** - Motivation responsabilisante
- 🎯 **Personnalisation** - Par profil (particulier/entrepreneur) et humeur
- ⭐ **Favoris** - Sauvegarde des citations préférées
- 🌙 **Mode épreuve** - Messages plus profonds pour les moments difficiles

## 🚀 Démo

👉 **[Voir l'application](https://VOTRE_USERNAME.github.io/noor-app/)**

## 📁 Structure du projet

```
noor-app/
├── index.html          # Application React (single-file)
├── data/
│   └── citations.json  # Base de données des citations
└── README.md
```

## 🔧 Installation locale

```bash
# Cloner le repo
git clone https://github.com/VOTRE_USERNAME/noor-app.git

# Ouvrir dans le navigateur
open index.html
```

## 📊 API des citations

L'application charge les citations depuis `/data/citations.json`.

### Format des données

```json
{
  "version": "1.0.0",
  "last_updated": "2025-12-26T20:30:00Z",
  "total_count": 20,
  "citations": [
    {
      "id": "C001",
      "text_fr": "...",
      "text_ar": "...",
      "source_type": "coran|rappel|action",
      "source_ref": "Sourate X, verset Y",
      "moods": ["stress", "fatigue", "déprime", "motivation", "procrastination"],
      "target": ["particulier", "entrepreneur"],
      "epreuve": false
    }
  ]
}
```

## 🤖 Automatisation (n8n)

Le projet inclut des workflows n8n pour :
- **Génération** de nouvelles citations via OpenRouter/Claude
- **Vérification** de l'authenticité des citations religieuses
- **Export** automatique vers ce repository

## 📱 Captures d'écran

| Accueil | Citation | Favoris |
|---------|----------|---------|
| ![Home](screenshots/home.png) | ![Citation](screenshots/citation.png) | ![Favorites](screenshots/favorites.png) |

## 🛡️ Principes éditoriaux

- ✅ Citations authentiques uniquement (Coran, Hadith sahih)
- ✅ Sources systématiquement citées
- ✅ Aucune interprétation personnelle
- ✅ Aucune fatwa ni conseil religieux
- ❌ Pas de contenu généré sans vérification

## 📄 License

MIT License - Voir [LICENSE](LICENSE)

## 🤝 Contribuer

Les contributions sont les bienvenues ! Voir [CONTRIBUTING.md](CONTRIBUTING.md)

---

<p align="center">
  Fait avec ❤️ pour la communauté musulmane
</p>
