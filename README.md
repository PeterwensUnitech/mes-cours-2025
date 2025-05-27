# 📚 Mes Cours 2025 - Suivi Git & GitHub

Ce dépôt a été créé dans le cadre du mini-projet **"Utilisation de Git & GitHub pour le Suivi de vos Cours"**. Il illustre l'utilisation des outils Git et GitHub pour organiser, sauvegarder et collaborer sur des contenus de cours.

---

## 🗂️ Organisation des dossiers

Chaque cours dispose de son propre sous-répertoire :  
- `architecture-reseaux`  
- `gestion-de-projets-informatiques`  
- `Securite des systemes informatiques`  
- et d'autres dossiers selon mes cours  

Chaque sous-répertoire contient :
- Plans de cours
- Exercices, TPs, projets, etc.

---

## 📜 Commandes Git principales utilisées

```bash
# Cloner le dépôt
git clone https://github.com/..
cd mes-cours-2025

# Créer l'organisation des dossiers
mkdir architecture-reseaux gestion-de-projets-informatiques Securite des systemes informatiques

# Ajouter des fichiers
git add .
git commit -m "Ajout des fichiers de cours : plans, notes, TPs"
git push origin main

# Consulter l’historique
git log --oneline

# Simuler un retour en arrière
git checkout <ID_commit>       # lecture seule
git checkout main              # revenir à la branche principale
# OU
git reset --hard <ID_commit>   # retour définitif
git push origin main --force
