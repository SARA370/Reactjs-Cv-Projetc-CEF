# 📌 ReactJS Project - CV en Ligne  

![React](https://img.shields.io/badge/React-18-blue.svg)  
![Bootstrap](https://img.shields.io/badge/Bootstrap-5-purple.svg)  
![Status](https://img.shields.io/badge/Status-En%20cours-yellow)  
![License](https://img.shields.io/badge/Licence-MIT-green)

Ce projet est un site web personnel développé avec **React.js** pour **John Doe**, un développeur web en formation.  
Il permet de présenter son **portfolio**, ses **compétences**, ses **services**, et facilite le **contact avec les recruteurs**.

---

## 🚀 **Démonstration**
🔗 **Lien vers la version en ligne :** [John Doe Portfolio](https://votre-lien.netlify.app)  

---

## 🎯 **Objectifs du Projet**
- Créer un site web personnel pour présenter le portfolio et les compétences de John Doe.  
- Utiliser **React.js** pour le développement front-end.  
- Intégrer **Bootstrap** pour le design et le responsive.  
- Afficher les données du profil GitHub via l'API GitHub.  
- Héberger le site sur une plateforme comme **Netlify**, **Vercel**, ou **CodeSandbox**.  

---

## 🔥 **Fonctionnalités**
- ✅ **Accueil** : Présentation de John Doe avec une image de fond et un bouton "En savoir plus".  
- ✅ **À propos** : Section avec une photo, une description et des compétences affichées sous forme de barres de progression.  
- ✅ **Services** : Présentation des offres de services (UX Design, Développement Web, Référencement).  
- ✅ **Réalisations** : Portfolio avec au moins 3 projets présentés sous forme de cartes.  
- ✅ **Blog** : Section avec 6 articles présentés sous forme de cartes.  
- ✅ **Contact** : Formulaire de contact avec validation et carte Google Maps.  
- ✅ **Mentions Légales** : Informations sur l'éditeur, l'hébergeur et les crédits.  

---

## ⚡ **Dépendances Utilisées**
- **React.js** (`react`, `react-dom`)  
- **React Router** (`react-router-dom`) → Pour la navigation entre les pages.  
- **Bootstrap** (`bootstrap`) → Pour le design et le responsive.  
- **Font Awesome** (`@fortawesome/fontawesome-free`) → Pour les icônes.  
- **Fetch API** → Pour récupérer les données du profil GitHub.  

---

## 💻 **Installation et Démarrage**
1. **Clonez ce dépôt** :
   ```bash
   git clone https://github.com/SARA370/Reactjs-Cv-Projetc-CEF.git && cd reactjs-project
   ```
2. **Installez les dépendances** :
   ```bash
   npm install
   ```
3. **Lancez le serveur de développement** :
   ```bash
   npm start
   ```
   📌 **Par défaut, React démarre sur** [http://localhost:3000](http://localhost:3000).  

---

## 📁 **Structure du Projet**
```
reactjs-project/
├── public/
│   ├── index.html
│   └── ...
├── src/
│   ├── components/   # Composants réutilisables
│   │   ├── Header.js
│   │   ├── Footer.js
│   │   ├── ContactForm.js
│   │   ├── BlogCard.js
│   │   ├── PortfolioCard.js
│   ├── pages/        # Pages principales
│   │   ├── Home.js
│   │   ├── About.js
│   │   ├── Services.js
│   │   ├── Portfolio.js
│   │   ├── Blog.js
│   │   ├── Contact.js
│   │   ├── MentionsLegales.js
│   ├── App.js
│   ├── index.js
│   └── ...
├── package.json
├── README.md
└── ...
```

---

## 🌍 **Hébergement**
Le site peut être hébergé sur **Netlify**, **Vercel**, ou **GitHub Pages**.  

**Déploiement sur Netlify :**
1. **Créer un compte** sur [Netlify](https://www.netlify.com/).  
2. **Lier le dépôt GitHub** au projet Netlify.  
3. **Déployer le site** en sélectionnant le dossier `build`.  
4. Netlify générera une **URL publique** pour votre site.  

---

## 📢 **Référencement (SEO)**
Le site est optimisé pour le **référencement naturel (SEO)** grâce à :  
- Balises **`<meta>`** pour la description et les mots-clés.  
- Utilisation de **balises sémantiques** (`<header>`, `<section>`, `<footer>`...).  
- **Validation du code** avec les outils **W3C**.  

---

## 🛠 **Scripts Disponibles**
- **`npm start`** → Démarre le serveur de développement.  
- **`npm run build`** → Génère une version de production dans le dossier `build`.  
- **`npm test`** → Lance les tests (si configurés).  
- **`npm run eject`** → Permet de personnaliser la configuration de Create React App (**opération irréversible**).  

---

## 💡 **Améliorations Possibles**
- ✅ Ajouter un **dark mode** pour une meilleure expérience utilisateur.  
- ✅ Permettre aux visiteurs de **laisser un commentaire sur les articles du blog**.  
- ✅ Ajouter un **système d’authentification** pour protéger certaines sections.  
- ✅ Intégrer un **CMS** pour gérer facilement les articles de blog.  

---

## 👤 **Auteur**
- **John Doe** : Développeur web en formation.  
- 📧 Contact : john.doe@gmail.com  
- 🔗 [GitHub](https://github.com/github-john-doe)  

---

## 📜 **Licence**
Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](LICENSE) pour plus de détails.  

---

## 🙌 **Remerciements**
- Les images libres de droit sont issues de [Pixabay](https://pixabay.com/).  
- Ce projet a été réalisé dans le cadre de la formation au **CEF** (Centre Européen de Formation).  