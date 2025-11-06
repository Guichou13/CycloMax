# Mockup Application ERP

## Description
Mockup d'une application ERP (Enterprise Resource Planning) moderne inspirée d'Odoo, avec une interface élégante et intuitive.

## Structure du projet

```
├── index.html          # Dashboard principal
├── clients.html        # Module de gestion des clients
├── catalogue.html      # Module de gestion du catalogue produits
├── stock.html          # Module de gestion des stocks
├── production.html     # Module de gestion de la production
├── fournisseurs.html   # Module de gestion des fournisseurs
├── styles.css          # Feuille de styles principale
└── README.md           # Ce fichier
```

## Modules disponibles

### 1. Dashboard (index.html)
- Vue d'ensemble avec statistiques clés
- Cartes de modules avec accès rapide
- Activité récente
- Métriques en temps réel

### 2. Clients (clients.html)
- Liste complète des clients
- Statistiques clients
- Graphiques d'évolution
- Gestion des devis

### 3. Catalogue (catalogue.html)
- Gestion des produits et services
- Catégorisation des produits
- Prix d'achat et de vente
- État des stocks par produit

### 4. Stock (stock.html)
- Suivi des inventaires
- Gestion multi-entrepôts
- Mouvements de stock
- Alertes de rupture

### 5. Production (production.html)
- Ordres de fabrication
- Lignes de production
- Suivi de progression
- Planification de production

### 6. Fournisseurs (fournisseurs.html)
- Gestion des fournisseurs
- Commandes d'approvisionnement
- Évaluation des fournisseurs
- Suivi des livraisons

## Fonctionnalités de l'interface

- **Navigation latérale** : Menu fixe avec accès à tous les modules
- **Responsive Design** : Interface adaptable aux différentes tailles d'écran
- **Cartes statistiques** : Indicateurs clés de performance
- **Tableaux de données** : Affichage structuré avec actions (voir, éditer, supprimer)
- **Système de badges** : Statuts visuels (actif, en attente, terminé, etc.)
- **Recherche intégrée** : Barre de recherche dans chaque module
- **Graphiques** : Zones réservées pour les graphiques de données

## Technologies utilisées

- **HTML5** : Structure des pages
- **CSS3** : Styles et mise en page
  - Flexbox
  - Grid
  - Variables CSS
  - Dégradés
  - Animations
- **Font Awesome 6.4.0** : Icônes

## Installation

1. Téléchargez tous les fichiers dans un même dossier
2. Ouvrez `index.html` dans votre navigateur web

Aucune installation supplémentaire n'est requise. Le projet utilise uniquement du HTML/CSS avec Font Awesome chargé via CDN.

## Palette de couleurs

- **Violet primaire** : `#7c3aed` - Actions principales
- **Bleu** : `#2563eb` - Informations
- **Vert** : `#10b981` - Succès
- **Orange** : `#f59e0b` - Avertissements
- **Rouge** : `#ef4444` - Erreurs/Alertes
- **Gris foncé** : `#1e293b` - Sidebar
- **Gris clair** : `#f8fafc` - Arrière-plan

## Personnalisation

Pour personnaliser les couleurs, modifiez les variables CSS dans `styles.css` :

```css
:root {
    --primary-color: #7c3aed;
    --secondary-color: #2563eb;
    --success-color: #10b981;
    --warning-color: #f59e0b;
    --danger-color: #ef4444;
    /* ... autres variables */
}
```

## Notes

Ce mockup est conçu à des fins de démonstration et de présentation. Les fonctionnalités sont simulées visuellement et ne sont pas connectées à une base de données réelle.

Pour une version fonctionnelle, il faudrait :
- Intégrer un backend (Node.js, Python, PHP, etc.)
- Ajouter une base de données
- Implémenter l'authentification
- Ajouter JavaScript pour les interactions dynamiques
- Intégrer une bibliothèque de graphiques (Chart.js, D3.js, etc.)

## Aperçu

Le mockup présente :
- ✅ Interface moderne et professionnelle
- ✅ Design inspiré d'Odoo
- ✅ Navigation intuitive
- ✅ Données d'exemple réalistes
- ✅ Responsive design
- ✅ 6 modules complets

---

**Développé par** : Assistant IA  
**Date** : Novembre 2025  
**Version** : 1.0

