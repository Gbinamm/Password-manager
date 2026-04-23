# Gestionnaire de mots de passe local

Ce projet est une application de gestion de mots de passe sécurisée fonctionnant exclusivement en local. Elle utilise Tauri pour la partie système (Rust) et des technologies web pour l'interface utilisateur.

## Prérequis

Avant de lancer le projet, assurez-vous que les outils suivants sont installés sur votre machine :

1. **Rust** : Téléchargez et installez-le via [rustup.rs](https://rustup.rs/).
2. **Node.js** : Utilisez la version LTS (Long Term Support).
3. **Dépendances système** :
   - Sur Windows : WebView2 est nécessaire (généralement inclus par défaut sur Windows 10 et 11).
   - Sur Linux : Les paquets `webkit2gtk` et `build-essential` sont requis.
   - Sur macOS : Les outils de ligne de commande Xcode sont nécessaires.

## Installation

1. Clonez le dépôt GitHub :
   ```bash
   git clone [URL_DU_DEPOT]
   cd [NOM_DU_DOSSIER]

2. Installez les dépendances nécessaires au projet :

   ```bash 
   npm install
   ```
## Développement
Pour lancer l'application en mode développement avec le rechargement automatique :

   ```bash 
npm run tauri dev   
```
## Compilation 
Pour générer l'exécutable final (le fichier .exe, .app ou .deb) :
   ```bash 
npm run tauri build
```
L'exécutable compilé se trouvera dans le dossier :
 ```bash 
src-tauri/target/release/bundle/
```