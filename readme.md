🚀 Atelier Pratique 1 – Premiers pas avec Git & GitHub

<p align="center">
  <img src="https://media.giphy.com/media/kH1DBkPNyZPOk0BxrM/giphy.gif" width="300">
</p>🎯 Objectif

Apprendre les bases de Git et GitHub :
✔️ Créer un dépôt
✔️ Ajouter et sauvegarder des fichiers
✔️ Comprendre les zones Git

---

⚙️ Configuration initiale

git config --global user.name "Prénom Nom"
git config --global user.email votre-email@exemple.com

🔍 Vérification :

git config --list

---

📁 Étapes du projet

1️⃣ Préparation

📂 Créer un dossier : "ex-git-prenom"
💻 Ouvrir avec VS Code

---

2️⃣ Initialiser Git

git init

<p align="center">
  <img src="https://media.giphy.com/media/3o7aD2saalBwwftBIY/giphy.gif" width="250">
</p>---

3️⃣ Ajouter un fichier

Créer "journal.txt" :

Aujourd'hui, j'apprends Git.

Ajouter au staging :

git add journal.txt

---

4️⃣ Premier Commit

git commit -m "Initial commit: création du journal"

<p align="center">
  <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="250">
</p>---

5️⃣ Modifier et comparer

Modifier :

Git est génial avec VS Code !

Comparer :

git diff

---

6️⃣ Annuler une erreur ❌

git checkout -- journal.txt

<p align="center">
  <img src="https://media.giphy.com/media/26ufdipQqU2lhNA4g/giphy.gif" width="250">
</p>---

🔁 Résumé rapide

Action| Commande
Initialiser| "git init"
Ajouter| "git add"
Commit| "git commit"
Vérifier| "git status"
Comparer| "git diff"
Annuler| "git checkout -- fichier"

---

🧠 Concepts clés

🟢 Working Directory → fichiers modifiés
🟡 Staging Area → prêts à être commit
🔵 Repository → historique

---

🎉 Résultat

✔️ Tu sais utiliser Git
✔️ Tu comprends les bases
✔️ Tu es prêt pour GitHub 🚀

<p align="center">
  <img src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif" width="300">
</p>---

⭐ Bonus

👉 Prochaine étape : pousser vers GitHub

git remote add origin <lien-repo>
git branch -M main
git push -u origin main
