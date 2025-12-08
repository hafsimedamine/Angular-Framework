# 🅰️ Angular Framework Project

![Angular](https://img.shields.io/badge/Angular-14%2B-red)
![TypeScript](https://img.shields.io/badge/TypeScript-4.7%2B-blue)
![NodeJS](https://img.shields.io/badge/Node.js-16%2B-green)

Ce dépôt contient une application Web développée avec le framework **Angular**. Il illustre les concepts fondamentaux du développement Front-End moderne : composants, services, routage et interaction avec des APIs.

## 🌟 Fonctionnalités

* **Architecture en Composants** : Réutilisation et modularité du code.
* **Routing** : Navigation fluide type SPA (Single Page Application).
* **Services & Injection de Dépendances** : Gestion de la logique métier et des données.
* **Data Binding** : Liaison bidirectionnelle entre le HTML et le TypeScript.
* **Communication HTTP** : Consommation de services REST (si applicable).

## 🚀 Installation et Lancement

Pour faire tourner ce projet localement, suivez ces étapes :

### Prérequis
Assurez-vous d'avoir installé :
* [Node.js](https://nodejs.org/) (version LTS recommandée)
* Angular CLI : `npm install -g @angular/cli`

### 1. Cloner et installer
```bash
git clone [https://github.com/hafsimedamine/Angular-Framework.git](https://github.com/hafsimedamine/Angular-Framework.git)
cd Angular-Framework
npm install

📂 Structure du Projet
```text
src/
├── app/
│   ├── components/    # Les vues de l'application
│   ├── services/      # Logique métier et appels API
│   ├── model/         # Classes et Interfaces de données
│   ├── app.module.ts  # Module racine
│   └── app-routing.module.ts # Configuration des routes
├── assets/            # Images, styles globaux
└── environments/      # Variables d'environnement (dev/prod)
```
