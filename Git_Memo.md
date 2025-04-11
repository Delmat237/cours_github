
# 🔧 Git & GitHub - Mémo Pratique

## 🔰 Introduction

Dans le développement logiciel moderne, **la gestion de version** est une compétence essentielle. **Git** est un système de contrôle de version distribué qui permet aux développeurs de suivre, organiser et collaborer efficacement sur des projets, qu'ils soient personnels ou en équipe. Grâce à **GitHub**, une plateforme basée sur Git, il est possible d’héberger du code, collaborer à distance, gérer les contributions via des pull requests et suivre l’évolution d’un projet dans le temps.

Utiliser Git et GitHub, c’est :
- Garantir la **traçabilité** des modifications.
- Faciliter la **collaboration en équipe**.
- Assurer une **sauvegarde continue** du code.
- Rendre possible le **travail en parallèle** via les branches.
- Automatiser les déploiements et les tests grâce à des workflows modernes (CI/CD).

Ce mémo présente les commandes Git les plus utilisées, pour te permettre de démarrer rapidement et de travailler de façon structurée et professionnelle.

---

## 🧰 Commandes Git utiles

### 🔹 Initialiser un dépôt
```bash
git init
```

### 🔹 Ajouter des fichiers
```bash
git add <nom_fichier>
git add .           # Pour ajouter toutes les modifications
```

### 🔹 Fusionner un dépôt distant dans le dépôt local
```bash
git pull
git pull origin <nom_branche>
```

### 🔹 Cloner un dépôt
```bash
git clone <url_depot>
```

### 🔹 Cloner une branche précise
```bash
git clone --branch nom_de_branche --single-branch https://url_du_repo.git
```

### 🔹 Voir l’état des fichiers
```bash
git status
```

### 🔹 Committer des changements
```bash
git commit -m "message de commit"
```

### 🔹 Branches
```bash
git branch                   # Lister
git branch <nom_branche>     # Créer
git checkout <nom_branche>   # Changer de branche
git checkout -b <nom_branche> # Créer et basculer
```

### 🔹 Fusionner des branches
```bash
git merge <nom_branche>
```

### 🔹 Pousser les changements vers GitHub
```bash
git push
git push origin <nom_branche>
```

### 🔹 Annuler ou restaurer
```bash
git rm --cached <nom_fichier>       # Supprimer du suivi sans supprimer le fichier
git restore <nom_fichier>           # Annuler les changements non commités
git checkout -- <nom_fichier>       # Revenir à la dernière version commitée
```

### 🔹 Historique
```bash
git log
```

### 🔹 Gérer un dépôt distant
```bash
git remote add origin <url_du_repo>
git remote remove origin
```

---

## 📬 Contact

- 📱 **WhatsApp** : +237 657 450 314  
- 💼 **LinkedIn** : [leonel-azangue](https://www.linkedin.com/in/leonel-azangue)  
- 🐙 **GitHub** : [Delmat237](https://github.com/Delmat237)  
- 📧 **Email** : azangueleonel9@gmail.com
