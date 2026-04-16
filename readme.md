📝 Mon Premier Journal de Bord (Git & GitHub)

📌 Objectif

Ce projet a pour but de :

- Découvrir Git et GitHub
- Comprendre les 3 zones : Working Directory, Staging, Repository
- Apprendre à versionner un projet avec VS Code

---

⚙️ Configuration initiale

Avant de commencer, configure ton identité Git :

git config --global user.name "Votre Nom"
git config --global user.email "votre-email@example.com"

Vérifier :

git config --list

---

📁 Étape 1 : Préparation

1. Ouvrir VS Code
2. Créer un dossier nommé : "ex-git-prenom"
3. Ouvrir ce dossier dans VS Code
4. Ouvrir le terminal intégré

---

🚀 Étape 2 : Initialiser le dépôt

git init

👉 Cela crée un dépôt Git local

---

📄 Étape 3 : Création du fichier et Staging

1. Créer un fichier : "journal.txt"
2. Ajouter dedans :

Aujourd'hui, j'apprends Git.

3. Ajouter le fichier au staging :

git add journal.txt

👉 Le fichier passe en Staged Changes

---

💾 Étape 4 : Premier Commit

git commit -m "Initial commit : création du journal"

👉 Le fichier est maintenant enregistré dans l’historique

---

✏️ Étape 5 : Modifier et comparer

1. Modifier "journal.txt" :

Git est génial avec VS Code !

2. Vérifier l’état :

git status

3. Voir les différences :

git diff

👉 Comparaison entre ancienne et nouvelle version

---

🔙 Étape 6 : Annuler les modifications

Pour annuler les changements :

git restore journal.txt

👉 Le fichier revient à la version du dernier commit

---

📊 Récapitulatif

Commande| Rôle
"git init"| Initialiser un dépôt
"git add"| Ajouter au staging
"git commit"| Sauvegarder une version
"git status"| Voir l’état des fichiers
"git diff"| Voir les modifications
"git restore"| Annuler les changements

---

📚 Conclusion

Ce TP permet de comprendre les bases de Git :

- Ajouter des fichiers
- Sauvegarder des versions
- Comparer et revenir en arrière

---

✨ Auteur : Loujain Dorrai
📅 Date :16/03/ 2026