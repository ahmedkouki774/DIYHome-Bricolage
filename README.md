# 🔨 DIYHome - Bricolage

Site e-commerce de bricolage moderne et responsive développé en HTML et CSS pur.

## 📋 Description

DIYHome est une boutique en ligne spécialisée dans les outils, peintures, pinceaux, vis et accessoires de bricolage. Les produits sont organisés par type de travaux pour faciliter la navigation.

## ✨ Fonctionnalités

- Page d'accueil moderne avec bannière hero
- 5 catégories de produits par type de travaux :
  - 🎨 Peinture & Décoration
  - 🪚 Menuiserie
  - 🔧 Plomberie
  - ⚡ Électricité
  - 🔩 Fixation & Visserie
- Section produits mis en avant
- Design responsive (mobile, tablette, desktop)
- Animations au survol
- Code propre et commenté pour débutants

## 🛠️ Technologies utilisées

- HTML5 (sémantique)
- CSS3 (Flexbox, Grid, Variables CSS)
- Google Fonts (Poppins)

## 📂 Structure du projet

```
Bricolage/
├── index.html          # Page d'accueil
├── css/
│   └── style.css       # Feuille de style principale
├── js/
│   └── script.js       # JavaScript (vide pour l'instant)
└── images/
    ├── produit1.jpg    # Perceuse-visseuse
    ├── produit2.jpg    # Kit peinture et pinceaux
    └── produit3.jpg    # Coffret de tournevis
```

## 🚀 Installation

1. Clonez le repository :
```bash
git clone https://github.com/ahmedkouki774/DIYHome-Bricolage.git
```

2. Ouvrez le fichier `index.html` dans votre navigateur

## 🎨 Personnalisation

### Modifier les couleurs

Éditez les variables CSS dans `css/style.css` (lignes 4-32) :

```css
:root {
    --color-primary: #2c3e50;    /* Couleur principale */
    --color-accent: #ff6b35;     /* Couleur d'accent */
}
```

### Modifier les prix

Changez les valeurs dans les balises `<p class="product-price">` du fichier `index.html`.

## 📱 Responsive Design

Le site s'adapte automatiquement aux différentes tailles d'écran :
- Mobile (< 768px)
- Tablette (768px - 1024px)
- Desktop (> 1024px)

## 📝 TODO

- [ ] Créer la page produits (liste complète)
- [ ] Créer la page détail produit
- [ ] Créer la page panier
- [ ] Créer la page commande
- [ ] Ajouter JavaScript pour les interactions

## 👤 Auteur

**Ahmed Kouki**
- GitHub: [@ahmedkouki774](https://github.com/ahmedkouki774)

## 📄 Licence

Ce projet est libre de droits et peut être utilisé à des fins éducatives.

---

© 2026 DIYHome - Tous droits réservés
