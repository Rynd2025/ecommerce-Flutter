# 🛒 ASWAN - Multi-Vendor E-commerce Application (KSA)

![Flutter](https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white)
![Dart](https://img.shields.io/badge/dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

> [cite_start]**Note :** Ce repository présente l'architecture technique et les fonctionnalités développées pour l'application **ASWAN** lors de mon expérience chez **Phylia Technology**[cite: 13, 14]. Le code source complet est privé.

---

## 📌 Présentation du Projet
**ASWAN** est une plateforme e-commerce multi-vendeur opérant en Arabie Saoudite (KSA). L'application permet une mise en relation fluide entre les marchands et les utilisateurs finaux pour la gestion des commandes, des produits et des paiements.

### Mon Rôle
[cite_start]En tant que **Développeuse Flutter**, j'ai été responsable de l'intégralité de la logique métier mobile et de la consommation des APIs REST fournies par l'équipe Backend (Laravel)[cite: 13, 15].

---

## 🛠️ Architecture Technique
[cite_start]L'application repose sur une **Clean Architecture** rigoureuse pour garantir la maintenabilité et la scalabilité du code[cite: 10, 34].

### Structure des Couches
1. [cite_start]**UI Layer** : Widgets Flutter et interfaces réactives (User & Merchant interfaces)[cite: 10].
2. [cite_start]**BLoC Layer** : Gestion de la logique métier et des états de l'application[cite: 10, 14, 32].
3. [cite_start]**Repository Layer** : Abstraction de la source des données (Data Mapping)[cite: 15].
4. [cite_start]**API Layer** : Consommation des services REST via le client **Dio**[cite: 15].

---

## ✨ Fonctionnalités Implémentées

### 👤 Interface Utilisateur (Customer)
* **Accueil & Catalogue** : Affichage dynamique des produits par catégories.
* **Panier (Cart)** : Gestion en temps réel de l'ajout/suppression et calcul des totaux.
* **Paiement (Payment)** : Intégration de flux sécurisés pour le marché Saoudien.

### 🏪 Interface Marchand (Merchant)
* [cite_start]**Gestion des Commandes** : Suivi des statuts (En attente, Traitée, Livraison)[cite: 16].
* **Tableau de Bord** : Visualisation des revenus et des statistiques de vente.

---

## 🚀 Optimisations & Impact
* [cite_start]**Performance** : Réduction du temps de chargement de l'UI de **25%** grâce à une gestion d'état optimisée avec **Bloc**[cite: 16].
* **Expérience Utilisateur** : Implémentation d'une interface bilingue (Arabe/Anglais) avec support du RTL (Right-to-Left).
* [cite_start]**Code Quality** : Application des principes **SOLID** et participation active aux revues de code[cite: 11, 18].

---

## 📸 Aperçu Visuel
| Écran de Connexion | Liste des Commandes (Marchand) |
| :---: | :---: |
| <img src="login.PNG" width="250" /> | <img src="cc.PNG" width="250" /> |

---

## 🛡️ Best Practices appliquées
* **Injection de dépendances** : Gestion propre des services et dépôts.
* **Modularité** : Séparation des fonctionnalités en modules indépendants pour faciliter les tests unitaires.
* [cite_start]**Agile** : Développement itératif avec des sprints réguliers[cite: 11, 24].

---
[cite_start]*Développé avec ❤️ par Rahma Ben Seghaier - Ingénieure Polytechnique Sousse* [cite: 2, 39]# ecommerce-Flutter
