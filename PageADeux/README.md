# 📖 Page à Deux - Mobile App (TypeScript)

**Page à Deux** est une application de suivi de lecture minimaliste et performante. Développée avec **React Native**, **Expo** et **TypeScript**, elle utilise une architecture modulaire (Hooks, Services, Composants) pour garantir une maintenance facile et une grande fluidité.

## 🚀 Fonctionnalités
- 📚 **Gestion de Bibliothèque** : Ajoutez vos livres et suivez votre progression globale.
- ⏱️ **Sessions de Lecture** : Notez vos pages lues quotidiennement.
- 📊 **Statistiques Avancées** : Visualisation des 7 derniers jours via un graphique à barres.
- 📳 **Haptic Feedback** : Retour tactile premium lors des interactions.
- 💾 **Persistance Locale** : Données sauvegardées via AsyncStorage avec un service typé.

## 🏗️ Architecture du Projet
Le projet suit une structure modulaire pour séparer la logique métier de l'interface utilisateur :

```text
src/
├── @types/          # Définitions des interfaces (Livre, Lecture, etc.)
├── components/      # Composants UI atomiques et réutilisables (ProgressBar, etc.)
├── constants/       # Thème, couleurs et configurations globales
├── hooks/           # Logique métier (useReadingData : calculs, filtres)
├── navigation/      # Configuration de la navigation par onglets
├── screens/         # Écrans principaux (Accueil, Statistiques)
└── services/        # Logique d'accès aux données (AsyncStorage)
```
## 🛠️ Installation et Démarrage

-  **Node.js (LTS)** 
-  **Expo Go** : sur votre smartphone pour tester en mode mobile.


## Lancement
-  **Bash** :  npx expo start
-  **Sur Desktop (Navigateur Web)** : 
     npx expo install react-native-web react-dom @expo/metro-runtime et 
     npx expo start --web


## Stack Technique
```text
Framework : Expo (React Native)

Langage : TypeScript (Typage strict pour la sécurité des données)

Navigation : React Navigation (Bottom Tabs)

Icônes : Lucide React Native

Stockage : AsyncStorage

Vibrations : Expo Haptics
```
##  📝 Roadmap
```
[ ] Système de "Streaks" (Série de jours de lecture consécutifs).

[ ] Mode Sombre (Dark Mode).

[ ] Notifications de rappel quotidiennes.

[ ] Exportation des données en format CSV/JSON.
```


