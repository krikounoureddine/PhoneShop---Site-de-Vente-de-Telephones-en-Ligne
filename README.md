<!-- README.md - PhoneShop -->

<body style="background: linear-gradient(135deg, #f0f9ff 0%, #e0f2fe 100%); margin: 0; padding: 20px;">

<div style="
    background-color: #ffffff;
    border-left: 4px solid #3b82f6;
    padding: 1.5rem;
    margin: 2rem 0;
    border-radius: 0 8px 8px 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
">

<p style="font-size: 1.2rem; color: #1e293b; font-weight: 500;">Site Web Innovant de Vente de Téléphones avec Réalité Augmentée & API Omeka S</p>

</div>

<br>

<div align="center" style="
    background: linear-gradient(90deg, #1d4ed8 0%, #3b82f6 100%);
    color: white;
    padding: 2.5rem 2rem;
    border-radius: 20px;
    box-shadow: 
        0 15px 35px rgba(59, 130, 246, 0.25),
        inset 0 1px 0 rgba(255, 255, 255, 0.3);
    border: 3px solid rgba(255, 255, 255, 0.2);
    position: relative;
    overflow: hidden;
">
    
<br>

<div style="position: absolute; top: 0; right: 0; padding: 1rem;">
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
    <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
    <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
    <img alt="Three.js" src="https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white">
    <img alt="Omeka S API" src="https://img.shields.io/badge/Omeka_S_API-4A154B?style=for-the-badge&logo=openaccess&logoColor=white">
</div>

<br>

<h1 style="margin-top: 2rem; font-size: 2.8rem;">📱 PhoneShop</h1>
<p style="font-size: 1.1rem; opacity: 0.95; max-width: 800px; margin: 1rem auto; line-height: 1.6;">
**👨‍💻 Présenté par Krikou Nourddine et Mokrani Islam**<br><br>
Une plateforme web révolutionnaire de vente de téléphones qui combine e-commerce traditionnel avec des technologies de pointe : <strong>réalité augmentée 3D</strong>, <strong>recherche vocale</strong> et <strong>géolocalisation intelligente</strong>. Basé sur l'architecture <strong>MVC</strong> et alimenté par l'<strong>API Omeka S</strong> pour une gestion flexible des données.
</p>

</div>

</body>

---

## 📖 Table des Matières

### 🚀 **Découverte & Présentation**
- [🎯 Description du Projet](#-description-du-projet)
- [✨ Fonctionnalités Principales](#-fonctionnalités-principales)
- [📱 Démonstration Visuelle](#-démonstration-visuelle)

### ⚙️ **Architecture & Développement**
- [🏗️ Design Pattern & Architecture](#️-design-pattern--architecture)
- [🛠️ Technologies Utilisées](#️-technologies-utilisées)
- [🔧 Installation & Configuration](#-installation--configuration)

### 🌐 **Ressources & Interaction**
- [📝 Formulaire de Feedback](#-formulaire-de-feedback)
- [🤝 Collaboration](#-collaboration)
- [📞 Contact](#-contact)

---

## 🎯 Description du Projet

**PhoneShop** est une plateforme de vente en ligne innovante dédiée aux **📱 téléphones mobiles et accessoires**. Le site transcende l'expérience d'achat classique en intégrant des technologies avancées comme la **🕶️ réalité augmentée 3D**, la **🎙️ recherche vocale** et la **📍 géolocalisation** pour optimiser l'achat et la collecte des produits.

### 🔑 **Innovation Technique : API Omeka S**
Ce qui distingue PhoneShop, c'est son approche backend novatrice. Au lieu d'une base de données traditionnelle, le site utilise l'**API Omeka S** pour gérer dynamiquement son catalogue de produits. Chaque requête est sécurisée par une **🔑 clé d'authentification** et un **🆔 identifiant unique**, garantissant une gestion rapide, fiable et flexible des données numériques.

Cette architecture permet une **📂 organisation modulaire** des ressources produits (spécifications, images, modèles 3D) et facilite les mises à jour et l'évolutivité du catalogue.

---

## ✨ Fonctionnalités Principales  

### 🔹 **Expérience Utilisateur Immersive**
- **🕶️ Visualisation en Réalité Augmentée 3D** : Explorez les produits sous tous les angles avec des modèles **GLTF** générés via Blender. Intégration fluide via **Three.js** pour une expérience web immersive.
- **🎙️ Recherche Vocale Intelligente** : Trouvez instantanément le produit idéal en utilisant simplement votre voix, grâce à l'API **SpeechRecognition** du navigateur.
- **📍 Géolocalisation & Récupération en Magasin** : Le système calcule automatiquement l'itinéraire le plus court vers les points de vente partenaires, avec estimation précise du temps de trajet via **OpenStreetMap**.

### 🔹 **Gestion des Achats & Comptes**
- **🛒 Panier d'Achat Dynamique** : Ajoutez, modifiez les quantités ou retirez des produits en temps réel. Interface intuitive pour une gestion fluide avant la finalisation de la commande.
- **👤 Système de Comptes Dual** : Créez un profil en tant qu'**Acheteur** pour suivre vos commandes et favoris, ou en tant que **Vendeur** pour gérer votre inventaire et interactions.

### 🔹 **Performance & Accessibilité**
- **📱 Design 100% Responsive** : Une expérience utilisateur optimisée et fluide sur tous les appareils, du smartphone au desktop.
- **⚡ Chargement Optimisé** : Architecture légère et requêtes API efficaces pour des temps de chargement rapides.

---

## 📱 Démonstration Visuelle

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Interface Principale</strong><br><img src="https://github.com/user-attachments/assets/c75e0560-4591-494e-b534-df2872aeb105" width="300" alt="Aperçu Omeka S" style="object-fit: contain; background: #f8fafc; border-radius: 12px; border: 2px solid #e2e8f0; padding: 10px;"></td>
    </tr>
    <tr>
      <td align="center"><em>Logo et identité visuelle de PhoneShop</em></td>
    </tr>
  </table>

  <br>

  <table>
    <tr>
      <td align="center"><strong>Réalité Augmentée</strong><br><div style="width:280px; height:200px; background: linear-gradient(135deg, #1e293b, #334155); display:flex; align-items:center; justify-content:center; border-radius:12px; border:2px solid #3b82f6;"><span style="color:#94a3b8; text-align:center;">🕶️ Visualisation 3D<br><small>Modèle téléphone en GLTF</small></span></div></td>
      <td align="center"><strong>Interface Catalogue</strong><br><div style="width:280px; height:200px; background: #f8fafc; display:flex; align-items:center; justify-content:center; border-radius:12px; border:2px dashed #cbd5e1;"><span style="color:#64748b; text-align:center;">📱 Grille de produits<br><small>Filtres et recherche</small></span></div></td>
      <td align="center"><strong>Géolocalisation</strong><br><div style="width:280px; height:200px; background: #f0f9ff; display:flex; align-items:center; justify-content:center; border-radius:12px; border:2px dashed #7dd3fc;"><span style="color:#0369a1; text-align:center;">📍 Carte des magasins<br><small>Itinéraire optimisé</small></span></div></td>
    </tr>
    <tr>
      <td align="center"><em>Visualisation produit 3D</em></td>
      <td align="center"><em>Navigation dans le catalogue</em></td>
      <td align="center"><em>Trouver un magasin proche</em></td>
    </tr>
  </table>
</div>

*ℹ️ Les captures d'écran interactives de l'interface utilisateur peuvent être ajoutées dans le dossier `screenshots/`.*

---

## 🏗️ Design Pattern & Architecture

PhoneShop est construit sur une **architecture MVC (Modèle-Vue-Contrôleur)** robuste, parfaitement adaptée aux applications web modernes et dynamiques.

### 📂 **Structure MVC de PhoneShop**

| Couche | Composants | Responsabilités |
|--------|------------|-----------------|
| **Modèle (Model)** | - Logique d'appel à l'**API Omeka S**<br>- Gestion des données produits/panier<br>- Calculs géolocalisation | Gère toutes les données, la logique métier et la communication avec l'API externe. C'est la source unique de vérité. |
| **Vue (View)** | - Templates **HTML** dynamiques<br>- Styles **CSS** responsifs<br>- Scripts d'interaction **JavaScript** | Présente les données de manière attractive et interactive à l'utilisateur. Ne contient aucune logique métier. |
| **Contrôleur (Controller)** | - Gestionnaires d'événements<br>- Routage des actions utilisateur<br>- Coordination Modèle ↔ Vue | Reçoit les entrées utilisateur, interroge le Modèle, et met à jour la Vue en conséquence. |

### 🔄 **Flux de Données avec Omeka S**
1.  L'utilisateur recherche un produit (texte ou voix).
2.  Le **Contrôleur** capture cette action.
3.  Le **Modèle** formule et envoie une requête authentifiée à l'**API Omeka S**.
4.  Omeka S renvoie les données produits (JSON).
5.  Le **Modèle** traite et structure ces données.
6.  Le **Contrôleur** passe ces données à la **Vue**.
7.  La **Vue** les affiche (liste, fiche détaillée ou vue 3D).

**Avantages de cette architecture :**
- **Maintenabilité** : Code clairement séparé et organisé.
- **Évolutivité** : Facile d'ajouter de nouvelles fonctionnalités (ex: un système de paiement).
- **Testabilité** : Chaque couche peut être testée indépendamment.

---

## 🛠️ Technologies Utilisées  

### 🌐 **Frontend & Interface**
| Technologie | Rôle dans PhoneShop |
|-------------|---------------------|
| **HTML5** | Structure sémantique et accessible des pages web. |
| **CSS3** | Mise en forme, design responsive et animations modernes. |
| **JavaScript (ES6+)** | Logique interactive, gestion des événements et communication asynchrone. |
| **Three.js** | Bibliothèque 3D pour le rendu WebGL et l'intégration des modèles en réalité augmentée. |

### ⚙️ **Backend, Données & APIs**
| Technologie | Rôle dans PhoneShop |
|-------------|---------------------|
| **API Omeka S** | **Cœur du backend.** Gère le catalogue de produits, les métadonnées et les médias de manière sécurisée et flexible via des endpoints REST. |
| **Fetch API / Axios** | Effectue les requêtes HTTP (GET, POST) sécurisées vers l'API Omeka S. |
| **SpeechRecognition API** | Interface du navigateur pour capter et transcrire la voix en texte (recherche vocale). |
| **Geolocation API & OpenStreetMap** | Récupère la position de l'utilisateur et calcule les itinéraires vers les magasins. |

### 🎨 **Design & Modélisation**
| Outil | Utilisation |
|-------|-------------|
| **Blender** | Création et export des modèles 3D des téléphones au format **GLTF/GLB**. |
| **Figma / Adobe XD** | Conception des maquettes et du prototype de l'interface utilisateur. |
| **Git & GitHub** | Contrôle de version et collaboration entre développeurs. |

---

## 🔧 Installation & Configuration

### **Prérequis**
- Un navigateur web moderne (Chrome 80+, Firefox 75+, Edge 80+)
- Un serveur web local (comme [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) pour VS Code, XAMPP, ou un simple `python -m http.server`)
- Une **clé API valide** et un **identifiant** pour l'instance Omeka S (à obtenir auprès de l'administrateur)

### **Étapes pour Développeurs**

1.  **Cloner le dépôt :**
    ```bash
    git clone https://github.com/krikounoureddine/Projet-du-module-Langages-et-Developpement-Web.git
    cd Projet-du-module-Langages-et-Developpement-Web
    ```

2.  **Configurer l'accès à l'API Omeka S :**
    - Localisez le fichier de configuration JavaScript (ex: `config.js` ou `apiConfig.js`).
    - Remplacez les placeholders par vos identifiants :
    ```javascript
    const OMEKA_CONFIG = {
        BASE_URL: 'https://votre-instance-omeka-s.org/api',
        API_KEY: 'votre_cle_api_secrete_ici',
        IDENTIFIER: 'votre_identifiant_ici'
    };
    ```

3.  **Lancer l'application :**
    - Ouvrez le dossier du projet dans votre éditeur de code.
    - Lancez un serveur local (ex: avec l'extension Live Server de VS Code).
    - Ouvrez `index.html` via le serveur (généralement `http://localhost:5500` ou similaire).

### **Notes Importantes :**
- **Sécurité** : Ne commitez jamais votre clé API réelle dans un dépôt public. Utilisez un fichier `.gitignore` pour exclure `config.js` et travaillez avec des variables d'environnement ou un fichier de configuration exemple (`config.example.js`).
- **CORS** : Assurez-vous que votre instance Omeka S est configurée pour autoriser les requêtes depuis votre domaine de développement (`localhost`).

---

## 📝 Formulaire de Feedback

Nous accordons une grande importance à votre avis pour améliorer PhoneShop ! Partagez vos impressions, suggestions ou signalez un bug via notre formulaire dédié.

<div align="center" style="margin: 2rem 0;">

### 🔗 Accéder au Formulaire

[![Google Forms](https://img.shields.io/badge/📝_Remplir_le_Formulaire_de_Feedback-4285F4?style=for-the-badge&logo=googleforms&logoColor=white)](https://docs.google.com/forms/d/e/1FAIpQLScCpb0oUcjKjKOS3jqYVUL2JjcRk41NjudZenlLXVeQymFDgw/viewform?usp=sf_link)

*Votre contribution est précieuse pour l'évolution du projet.*

### 📲 QR Code du Formulaire
![QR Code du formulaire](docs/qrcode.png)
*Scannez-moi pour accéder rapidement au formulaire*

</div>

---

## 🤝 Collaboration

**PhoneShop** est le fruit d'une collaboration entre **Krikou Nourddine** et **Mokrani Islam**. Ce projet académique démontre notre capacité à :

1.  **Collaborer efficacement** en équipe sur une architecture logicielle complexe.
2.  **Intégrer des technologies variées** (Frontend, API externe, 3D, géolocalisation) en un produit cohérent.
3.  **Documenter et présenter** un projet technique de manière claire et professionnelle.

### **Pour les Développeurs Intéressés**
Le code source est ouvert pour consultation. Si le concept vous intéresse pour une collaboration future, une évolution ou une réutilisation, n'hésitez pas à nous contacter.

---

## 📞 Contact

### 👥 **Équipe du Projet PhoneShop**

| Membre | Rôle Principal | Lien |
|--------|----------------|------|
| **Krikou Nourddine** | Développeur Full-Stack, Architecture API & 3D | [![GitHub Nourddine](https://img.shields.io/badge/GitHub-Nourddine-181717?style=flat-square&logo=github)](https://github.com/krikounoureddine) |
| **Mokrani Islam** | Développeur Frontend, Design UI/UX & Expérience Utilisateur | *Lien GitHub/Portfolio à ajouter* |

📧 **Pour toute question concernant le projet :**
[contact@krikou.dev](mailto:contact@krikou.dev)

---

## ⭐ L'Innovation au Service du E-commerce

PhoneShop n'est pas un simple site de vente. C'est une **preuve de concept technique** qui explore le futur des interfaces d'achat en ligne en combinant :

- **🔥 Une Stack Technique Moderne** : Intégration maîtrisée d'APIs natives du navigateur et externes.
- **🎨 Une Expérience Utilisateur Avancée** : Priorité donnée à l'immersion (3D), la praticité (voix) et l'efficacité (géolocalisation).
- **🏗️ Une Architecture Robuste** : Utilisation pertinente du pattern MVC et d'une API headless (Omeka S) pour une séparation claire des préoccupations.

> 💡 **Ce projet vous a intéressé ?** Pensez à **starifier** le [dépôt GitHub](https://github.com/krikounoureddine/Projet-du-module-Langages-et-Developpement-Web) pour soutenir notre travail !

<div align="center" style="margin-top: 3rem; padding: 2rem; background: linear-gradient(to right, #f0f9ff, #e0f2fe); border-radius: 16px; border: 2px solid #bae6fd;">

---

## 📱 PhoneShop • Redéfinir l'expérience d'achat de téléphones.

[![Code Source](https://img.shields.io/badge/📂_Voir_le_Code_Source_Complet-1e40af?style=for-the-badge)](https://github.com/krikounoureddine/Projet-du-module-Langages-et-Developpement-Web)
[![Site Démo](https://img.shields.io/badge/🌐_Visiter_le_Site_Démo-10b981?style=for-the-badge&logo=web)](https://krikounoureddine.github.io/Projet-du-module-Langages-et-Developpement-Web/)

</div>

# 📱 PhoneShop - Site de Vente de Téléphones en Ligne

**👨‍💻 Présenté par Krikou Nourddine et Mokrani Islam**

![omeka s](https://github.com/user-attachments/assets/c75e0560-4591-494e-b534-df2872aeb105)

## 🛒 Description

 **PhoneShop** est une plateforme de vente en ligne innovante dédiée aux **📱 téléphones mobiles et accessoires**. En plus de l'achat classique, le site propose une expérience immersive grâce à des technologies avancées telles que **🕶️ réalité augmentée 3D**, **🎙️ recherche vocale** et **📍 géolocalisation** pour optimiser l'achat et la collecte des produits en magasin. Ce qui distingue PhoneShop, c'est l'intégration d'appels à l'**API Omeka S** au lieu d'utiliser une base de données traditionnelle. Chaque requête vers **Omeka S** est sécurisée grâce à une **🔑 clé d'authentification** et un **🆔 identifiant unique**, garantissant une gestion rapide et fiable des données.

L'approche basée sur **Omeka S** offre une **📂 flexibilité accrue** pour organiser et afficher les données tout en optimisant la gestion des ressources numériques.

## 🚀 Fonctionnalités

### 🔹 Fonctionnalités principales
- **🕶️ Réalité Augmentée 3D** : Visualisation des produits en **3D** avec des fichiers **GLTF** créés avec Blender pour une immersion complète dans les produits.
- **🎙️ Recherche vocale** : Recherche de produits via des commandes vocales pour une navigation plus intuitive.
- **📍 Géolocalisation et récupération en magasin** : Calcul du trajet le plus court vers les magasins physiques proches pour récupérer les produits, avec estimation du temps de trajet.
- **🛒 Panier d'achat** : Ajout, modification, et suppression de produits dans le panier avant de finaliser la commande.

### 🔹 Fonctionnalités additionnelles
- **👤 Gestion des comptes** : Création de profils distincts pour les acheteurs et les vendeurs pour gérer les transactions et les interactions.

## 🎯 Design de pattern utilisé
- **📂 MVC (Modèle-Vue-Contrôleur)** : Séparation de la logique de l'application (Modèle), de la présentation des données (Vue) et de la gestion des interactions utilisateur (Contrôleur).
- **📱 Responsivité** : Le site est conçu pour être entièrement **responsive** et optimisé pour les appareils mobiles, garantissant une expérience fluide pour tous les utilisateurs.

## 🛠 Technologies utilisées
- **🎨 Frontend** : HTML, CSS, JavaScript
- **⚙️ Backend** : JavaScript, Fetch API
- **📡 Récupération des Données** : API OMEKA S
- **🕶️ Réalité augmentée** : Blender pour les modèles 3D, format GLTF, Three.js
- **📍 Géolocalisation** : APIs OpenStreetMap
- **🎙️ Recherche vocale** : Reconnaissance vocale avec SpeechRecognition

## 🔧 Installation

Clonez ce projet sur votre machine locale :

```bash
git clone https://github.com/krikounoureddine/Projet-du-module-Langages-et-Developpement-Web.git
```

## 📝 Formulaire

Pour remplir le formulaire, [📩 cliquez ici](https://docs.google.com/forms/d/e/1FAIpQLScCpb0oUcjKjKOS3jqYVUL2JjcRk41NjudZenlLXVeQymFDgw/viewform?usp=sf_link).

### 🔗 Le lien du formulaire :

🔗 [Accéder au formulaire](https://docs.google.com/forms/d/e/1FAIpQLScCpb0oUcjKjKOS3jqYVUL2JjcRk41NjudZenlLXVeQymFDgw/viewform?usp=sf_link)

### 📲 QR code du formulaire :

 ![image alt](docs/qrcode.png)
